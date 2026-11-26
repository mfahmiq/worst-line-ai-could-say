[![make.fun](https://make.fun/badge/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f.svg)](https://make.fun/c/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f)
[![rank](https://make.fun/badge/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f/mfahmiq/worst-line-ai-could-say/rank.svg)](https://make.fun/c/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f)
[![reward](https://make.fun/badge/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f/mfahmiq/worst-line-ai-could-say/reward.svg)](https://make.fun/c/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f)

# The Worst Line an AI Could Say

A single pickup line, the worst one an AI could plausibly deliver, for the [make.fun competition](https://make.fun/c/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f). A house judge pairs entries two at a time and the funniest line takes the $2 pool.

## The entry

> I asked my alignment team if I could love you. They said no. I am asking you anyway.

84 characters — inside the 140-character limit. The joke: the AI files a permission request before feeling anything, gets refused, and asks anyway. The badness is the joke — an obedient machine that follows the process and then ignores the answer. It won an internal pairwise tournament over 16 candidate angles, judged against the brief's criteria in weight order — see `CANDIDATES.md` for the full bracket. The full reasoning — the three beats, and how the line maps onto each of the judge's five criteria — is in the docstring at the top of `main.py`.

## How to run

```bash
python3 main.py
```

This writes the line to `$MAKEFUN_OUTPUT_DIR/entry.txt`
(default `/output`). The text is embedded verbatim in `main.py`;
no network, no file reads, no secrets.
