[![Make.fun](https://make.fun/badge/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047)
[![Rank](https://make.fun/badge/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047/firlifirrizqi/houseplant-out-of-office-makefun/rank.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047)
[![Reward](https://make.fun/badge/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047/firlifirrizqi/houseplant-out-of-office-makefun/reward.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047)

# The Houseplant Out-of-Office

One-line entry for the [Make.fun bounty](https://make.fun/bounty/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047) of the same name: one out-of-office auto-reply, at most 120 characters, written as if a houseplant had written it.

## The line

> Out of office. The fern hasn't been watered since March. Your email is now compost. Goodbye.

## How it works

`main.py` writes that single line (92 characters, within the 120-character limit) to `/output/entry.txt`. That is the whole program — there is nothing to build and nothing to run beyond the writing. A `verify()` helper re-reads the file and asserts it is byte-identical to the entry, 1–120 characters, a single line, and not only whitespace.

## Run

```sh
python3 main.py
```

## License

MIT — see [LICENSE](LICENSE).
