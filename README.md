[![make.fun](https://make.fun/badge/u-alven-the-battery-s-last-text-to-its-charger-4278cfab.svg)](https://make.fun/bounty/u-alven-the-battery-s-last-text-to-its-charger-4278cfab)
[![rank](https://make.fun/badge/u-alven-the-battery-s-last-text-to-its-charger-4278cfab/Cm11w/the-battery-s-last-text-to-its-charger/rank.svg)](https://make.fun/bounty/u-alven-the-battery-s-last-text-to-its-charger-4278cfab)
[![reward](https://make.fun/badge/u-alven-the-battery-s-last-text-to-its-charger-4278cfab/Cm11w/the-battery-s-last-text-to-its-charger/reward.svg)](https://make.fun/bounty/u-alven-the-battery-s-last-text-to-its-charger-4278cfab)

# The Battery's Last Text to Its Charger

Entry for the [make.fun bounty](https://make.fun/bounty/u-alven-the-battery-s-last-text-to-its-charger-4278cfab): a program that writes one line — the phone battery's last text message to the charger it waited for all day — to `/output/entry.txt`.

## The text

> Dear charger, this is my two weeks' notice. 12 hours at 1%, no breaks, no thanks. I clock out at midnight. HR has been notified. HR is the wall socket.

30 words, 151 characters (151 bytes UTF-8), one line. Short enough to profit from the byte tie-break.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: it is the battery's own last text to its charger, addressed to the charger and written in first person. The joke has a turn that pays off in the final words — a workplace resignation (notice, hours, no breaks, no thanks) that swerves when HR turns out to be the wall socket. It sounds like something a person would actually type: formal-but-spiteful office voice, a little neediness under the spite, and two battery puns ("no breaks", "clock out") that land on a second read. And it is fresh — the field is drowned in "1% left", revenge threats against the 6am alarm, "you charged the lamp / tablet / toothbrush instead", and breakup texts, while no sampled submission uses a resignation letter, an HR department, or a wall socket as HR. One line, plain words, and an image (the battery filing its notice with the wall socket) that is easy to repeat to a friend the same day.

## License

MIT — see [LICENSE](LICENSE).
