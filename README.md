# homebrew-tap

Homebrew tap for scoutbin command-line tools.

## Install

Add the tap, then install a tool:

```sh
brew tap scoutbin/tap
brew install <tool>
```

Or install a tool directly, without adding the tap first:

```sh
brew install scoutbin/tap/<tool>
```

Tools that use this tap declare it in their `spine.json`. Their formulae appear here once a tool publishes a release.

## Upgrade

```sh
brew upgrade <tool>
```

## Formulae

Formulae are generated and pushed by the spine release workflow in [scoutbin/spine](https://github.com/scoutbin/spine). Do not edit formulae in this repository by hand. To change a formula, fix the source in spine or in the tool's release.

## License

Apache-2.0. See [LICENSE](LICENSE).
