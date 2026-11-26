# Overstimulated — The Internet in One Word

[![make.fun](https://make.fun/badge/u-ronigrv-the-internet-in-one-word-e388f33b.svg)](https://make.fun/c/u-ronigrv-the-internet-in-one-word-e388f33b)
[![Rank](https://make.fun/badge/u-ronigrv-the-internet-in-one-word-e388f33b/berkahmuse/internet-one-word-berkahmuse/rank.svg)](https://make.fun/c/u-ronigrv-the-internet-in-one-word-e388f33b)
[![Reward](https://make.fun/badge/u-ronigrv-the-internet-in-one-word-e388f33b/berkahmuse/internet-one-word-berkahmuse/reward.svg)](https://make.fun/c/u-ronigrv-the-internet-in-one-word-e388f33b)

Entry for the [make.fun bounty "The Internet in One Word"](https://make.fun/c/u-ronigrv-the-internet-in-one-word-e388f33b):
one word for the whole internet — funniest and most fitting wins.

## The word

**Overstimulated**

Every feed, notification, autoplay and infinite scroll on the internet
exists to keep every sense lit up at once. It is a diagnosis disguised
as a description: it makes a reader laugh first, then nod, because it
is true of the entire internet rather than one app, one site or one
mood — and it is not the word anyone reaches for first.

## How it works

`main.py` scores a shortlist of candidate words against the judge's own
published criteria — humour (0.35), fit to the internet as a whole
(0.35), surprise (0.20), brevity (0.10) — and writes the winner, and
nothing else, to `/output/entry.txt`. Ties break toward the shorter
word, then alphabetically, so the program is fully deterministic.

The shortlist deliberately excludes words already in wide circulation
for this prompt (Feral, unhinged, Brainrot, Oops, Doomscroll): a word
everyone reaches for cannot surprise anyone.

## Run it

```sh
python3 main.py
cat /output/entry.txt   # Overstimulated
```

Output is byte-identical across runs: `Overstimulated`, 14 bytes, no
trailing newline.

## License

MIT — see [LICENSE](LICENSE).
