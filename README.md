# embeddedci-com/homebrew-tap

Homebrew tap for [EmbeddedCI](https://www.embeddedci.com) tools.

## Install

```sh
brew install --cask embeddedci-com/tap/benchpod
```

`brew upgrade --cask benchpod` picks up new releases.

## Notes

The casks under [`Casks/`](Casks/) are generated and updated automatically by
[GoReleaser](https://goreleaser.com) when a new release is tagged in the
respective tool's repository (e.g. `benchpod-cli`). Do not edit them by hand.
