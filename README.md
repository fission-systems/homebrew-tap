# Homebrew tap for Fission

```bash
brew install fission-systems/tap/fission-cli
```

This installs `fission_cli` and its resources (Sleigh processor specifications
and signatures) under the Homebrew prefix. The binary finds them on its own.

`Formula/fission-cli.rb` is generated for each release by
[Fission's CD workflow](https://github.com/fission-systems/Fission/blob/main/.github/workflows/cd.yml)
from the release's archive checksums. Do not edit it by hand.

The formula is `fission-cli`, not `fission`: Homebrew already has an unrelated
cask with that name.

Project: <https://github.com/fission-systems/Fission>
