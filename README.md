# homebrew-tap

Homebrew formulae for [Yusuf Demirci](https://github.com/meyusufdemirci)'s tools.

```sh
brew install meyusufdemirci/tap/claude-code-session-tracker
```

| Formula | What it is |
| --- | --- |
| [`claude-code-session-tracker`](./Formula/claude-code-session-tracker.rb) | See every Claude Code session on your machine in a local dashboard — [source](https://github.com/meyusufdemirci/claude-code-session-tracker) |

## How this repository is maintained

Nothing here is written by hand. Each formula is rendered from the package it
installs by `scripts/formula.mjs` in the source repository, and pushed here by
that repository's release workflow the moment a version reaches npm — so the
`url` and `sha256` always describe bytes that have actually been published.

To change a formula, change the generator that produces it. An edit committed
here is overwritten by the next release.

## MIT
