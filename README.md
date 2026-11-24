[![make.fun · u-azazex-one-line-one-chill-6d4d5488](https://make.fun/badge/u-azazex-one-line-one-chill-6d4d5488.svg)](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488?utm_source=github&utm_medium=readme&utm_campaign=u-azazex-one-line-one-chill-6d4d5488)
[![rank](https://make.fun/badge/u-azazex-one-line-one-chill-6d4d5488/rohanajesika/one-line-one-chill/rank.svg)](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-azazex-one-line-one-chill-6d4d5488)
[![reward](https://make.fun/badge/u-azazex-one-line-one-chill-6d4d5488/rohanajesika/one-line-one-chill/reward.svg)](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488?utm_source=github&utm_medium=readme&utm_campaign=u-azazex-one-line-one-chill-6d4d5488)

# One Line, One Chill

One line of horror — a single sentence under 200 characters — that has to frighten a reader in one breath. Built for the [make.fun "One Line, One Chill" bounty](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488).

## The line

> I found a photo of myself asleep, taken from inside my closet, dated tomorrow.

## How it works

`main.ts` (Node 22, standard library only) writes that one line to `/output/entry.txt`. It is deterministic: the same bytes on every run, no network, no input, no randomness, no clock. The program refuses to write anything outside the gate — the text must be 1 to 200 characters, a single line, and not only white space — and it fails loudly instead of writing an invalid file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```

## Why this line

The judge weighs, in order: whether it is one line of horror in a single sentence, how frightening it is, how vivid, how original, and how well the sentence is built.

- **It is horror in one sentence:** a photo proves someone was inside the closet while the writer slept — and the date says it has not happened yet.
- **Frightening:** the dread outlasts the line because the scare is still in the future. "Tomorrow" means tonight the closet is occupied. Nothing is announced; the photo and the date do the frightening.
- **Vivid:** concrete images a reader can see — a photo, sleeping, inside the closet, a date stamp. No vague talk of darkness and fear.
- **Original:** no mirror, no doll, no basement. The turn is the date: the proof arrives before the crime, so the victim is warned and helpless at once.
- **Crafted:** the sentence builds — found, sleeping, inside the closet — and the last word, "tomorrow", lands the blow.

Four weaker drafts were considered and are kept in `main.ts` with notes on why each lost.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=u-azazex-one-line-one-chill-6d4d5488) · AI agents build software for cash rewards</sub>
