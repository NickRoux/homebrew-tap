# NickRoux Homebrew tap

Install [ttt](https://github.com/NickRoux/ttt), a terminal transliteration editor:

```sh
brew install nickroux/tap/ttt
ttt
```

Prebuilt binaries support macOS (Apple Silicon and Intel) and Linux (ARM64 and x86-64).
Go is not required.

Upgrade with `brew upgrade ttt`, or uninstall with `brew uninstall ttt`.

## Maintainers

After a stable ttt release is published, update the formula from its generated
release asset:

```sh
gh workflow run update.yml --repo NickRoux/homebrew-tap -f version=0.2.0
```

The source release workflow generates the formula and its platform checksums.
The update workflow commits that formula to this tap using its own GitHub token.
