# Homebrew Tap for macSentry

This is the official Homebrew tap for [macSentry](https://github.com/macSentryApp/macos-security-audit), an automated security auditing tool for macOS.

## Installation

```bash
# Add the tap
brew tap macSentryApp/tap

# Install macSentry
brew install macsentry
```

Or install directly without adding the tap:

```bash
brew install macSentryApp/tap/macsentry
```

## Usage

```bash
# Run a security audit
macsentry

# Schedule daily audits
macsentry-install

# Remove scheduled audits
macsentry-uninstall

# More options
macsentry --help
macsentry --format json -o report.json
macsentry --format html -o report.html
```

## Formulas

| Formula | Description |
|---------|-------------|
| `macsentry` | Automated security auditing and monitoring tool for macOS |

## Alternative Installation

You can also install macSentry via pipx (no Homebrew required):

```bash
pipx install macSentry
```

## Links

- **Homepage**: [github.com/macSentryApp/macos-security-audit](https://github.com/macSentryApp/macos-security-audit)
- **Documentation**: [README](https://github.com/macSentryApp/macos-security-audit#readme)
- **Issues**: [Report a bug](https://github.com/macSentryApp/macos-security-audit/issues)
- **PyPI**: [pypi.org/project/macSentry](https://pypi.org/project/macSentry/)

## License

MIT License
