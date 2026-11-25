# tatawurAI Homebrew tap

Homebrew formulas for tools from [tatawur.ai](https://tatawur.ai).

## Rafiq bridge

[Rafiq](https://github.com/tatawurAI/rafiq) lets you steer coding-agent sessions on your own server from your phone. The bridge is the small server that runs on your machine. This formula installs the self-contained bridge from a Rafiq release, with its own Java runtime, so you need no JDK.

```sh
brew install tatawurAI/tap/rafiq-bridge
rafiq-bridge setup
```

Then start it with either `brew services start rafiq-bridge` or `rafiq-bridge service install`, not both. See the [install guide](https://github.com/tatawurAI/rafiq/blob/main/docs/install.md) and the [setup guide](https://github.com/tatawurAI/rafiq/blob/main/docs/setup.md).

The formula appears here with the first Rafiq release.

## Maintainers

`Formula/rafiq-bridge.rb` is written by the Rafiq release workflow on each final release, with the real version and checksums. Do not edit it by hand. Prereleases are not published here. The template and the setup steps live in the Rafiq repository under `packaging/`.
