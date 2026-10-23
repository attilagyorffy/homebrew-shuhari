# homebrew-shuhari

Homebrew tap for [shuhari](https://shuhari.gyorffy.dev) (守破離), a CLI that manages agent skills across machines: a git-synced catalog lists the repositories that hold skills, and each machine links the skills it chooses into the directories its agents read.

## Install

```sh
brew install attilagyorffy/shuhari/shuhari
shuhari init <catalog-url>
```

Prebuilt binaries cover macOS (Apple silicon and Intel) and Linux (x86_64). No Rust toolchain or credentials are needed.

Homebrew reports third-party taps as untrusted. The install still works; to mark this tap trusted, run `brew trust --tap attilagyorffy/shuhari`.

## Update

```sh
brew update
brew upgrade shuhari
```

## Status

shuhari is in early testing. The source code is not public. The binaries here are provided for testing only; all rights reserved.

`Formula/shuhari.rb` and the release assets are published by the release workflow of the shuhari source repository. Do not edit the formula by hand.
