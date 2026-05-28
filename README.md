# homebrew-dimswitch

Homebrew tap for [Dimswitch](https://dimswitch.frnds.store) — attention-driven brightness control for external macOS displays.

## Install

```bash
brew tap f-rnd/dimswitch
brew install --cask dimswitch
```

## Update

```bash
brew upgrade --cask dimswitch
```

## Uninstall

```bash
brew uninstall --cask dimswitch         # remove the .app
brew uninstall --cask --zap dimswitch   # also wipe preferences and caches
```

## What gets installed

A notarized, Developer ID–signed universal `Dimmer.app` bundle (the marketing name is "Dimswitch"; the `.app` bundle and bundle identifier remain `Dimmer` for compatibility with existing installs).

DMGs are hosted on the FR&D distribution CDN (`frn-dist.sfo3.digitaloceanspaces.com`). The cask file in this repository is auto-synced from the upstream release pipeline; please file issues at [dimswitch.frnds.store](https://dimswitch.frnds.store) rather than here.
