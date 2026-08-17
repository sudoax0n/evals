# evals

<p align="center">
  <img src="assets/og-banner.png" alt="Two Foucault pendulums in a dark rotunda, one trail still on the meridian, one already sweeping." width="100%">
</p>

Same prompt. Two models. The HTML they wrote. The chats that wrote it.

Play-tests from [@beyondwudan](https://x.com/beyondwudan). One run each. Not a bench.

Open a folder, download the page, run it locally.

## Runs

| Date | Pair | Folder |
|------|------|--------|
| 2026-08-14 | Gemini 3.7 Flash High vs Grok 4.6 Extra High | [2026-08-14-foucault](2026-08-14-foucault) |

On that tape: Flash High stayed at 90°N (6°/s, 42/48 pins). Grok Extra High was dragged to 0° and printed `0°/day`, full turn none.

## Layout

```
YYYY-MM-DD-name/
  README.md       pair, date, what showed up on screen
  prompt.md       the exact paste
  <model-a>/      playable HTML
  <model-b>/      playable HTML
  chats/          exports from the models that wrote the HTML
```

Videos stay on X. This repo is the receipt.

## What is not here

Operator sessions. Tokens. Local paths. Scrapers.

Generation chats are stripped of machine paths before they land.

## License

MIT. See [LICENSE](LICENSE).
