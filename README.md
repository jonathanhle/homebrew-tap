# Homebrew Tap for Planguard

Official Homebrew tap for [Planguard](https://github.com/jonathanhle/planguard) - a pre-plan Terraform security scanner.

## Installation

```bash
brew tap jonathanhle/tap
brew install planguard
```

Or install directly:

```bash
brew install jonathanhle/tap/planguard
```

## Usage

After installation, you can use planguard:

```bash
planguard -directory ./terraform
```

## About Planguard

Planguard is a production-ready pre-plan Terraform security scanner with HCL-based configuration. It catches security issues and compliance violations before `terraform plan` runs.

Features:
- Pure HCL configuration - no code needed
- Pre-plan scanning
- Exception management with audit trails
- Multiple output formats (text, JSON, SARIF)
- GitHub Action support

## Documentation

Visit the [main repository](https://github.com/jonathanhle/planguard) for full documentation.

## Updating

This tap is automatically updated by GoReleaser when new versions of Planguard are released.
