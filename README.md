# skzv/homebrew-tap

Homebrew tap for [ccmux](https://github.com/skzv/ccmux) — a TUI for
Claude Code session management on top of tmux, Mosh, Tailscale, and
Obsidian.

> **Status: private during initial testing.** Public-install instructions
> will work once this tap goes public.

## Install (once public)

```sh
brew install skzv/tap/ccmux
```

`brew` auto-runs `brew tap skzv/tap` the first time you reference a
formula from this tap.

## How it's populated

Auto-published by [GoReleaser](https://goreleaser.com/) from the
[ccmux release workflow](https://github.com/skzv/ccmux/blob/main/.github/workflows/release.yml).
Don't hand-edit `Formula/*.rb` — changes are overwritten on the next
release. Open issues against
[skzv/ccmux](https://github.com/skzv/ccmux/issues) instead.
