# embeddedci-com/homebrew-tap

Homebrew tap for [EmbeddedCI](https://www.embeddedci.com) tools.

## Install

```sh
brew install --cask embeddedci-com/tap/benchpod        # BenchPod CLI
brew install --cask embeddedci-com/tap/emi-analyzer    # EMI Analyzer desktop app
```

`brew upgrade --cask <name>` picks up new releases.

## Notes

The casks under [`Casks/`](Casks/) are generated and updated automatically by
each tool's release: `benchpod` by [GoReleaser](https://goreleaser.com) in
`benchpod-cli`, `emi-analyzer` by the `homebrew` workflow in `emi-analyzer`.
Do not edit them by hand.
