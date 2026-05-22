# homebrew-cub

Homebrew tap for [Cub](https://github.com/ephraimduncan/cub.dev).

```bash
brew install --cask ephraimduncan/cub/cub
```

The cask installs the universal macOS `.dmg` from the latest [release](https://github.com/ephraimduncan/cub.dev/releases) and adds a `cub` CLI symlink. Upgrades land via `brew upgrade --cask cub`.

Cub is ad-hoc signed (no Apple Developer ID). The cask strips the macOS quarantine attribute on copy so the app launches without a Gatekeeper prompt on first run.
