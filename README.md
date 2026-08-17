# evals

One public repo for every play-test Abhinav (@beyondwudan) posts.

Local house stays at `E:\xevals`. This folder is the only thing that goes on GitHub.
Intended remote: `https://github.com/sudoax0n/evals` (not created yet — `gh` on this machine is logged in as a different account).

## What lives here

One folder per run:

```
YYYY-MM-DD-short-name/
  README.md          pair, date, one-line result
  prompt.md          the exact paste
  <model-a>/         playable HTML
  <model-b>/         playable HTML
  chats/             exports from the models that *wrote* the HTML
```

## What does not

- Rook / operator sessions
- Local paths, tokens, `.env`
- Videos (those go on X)
- Cost-card factories, scrapes, Arena automation

## New run

Copy the HTML you already generated. Drop the generation chats into `chats/` after stripping machine paths. Commit. Tweet 3 links this folder.
