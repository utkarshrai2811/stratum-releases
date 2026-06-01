# Stratum Releases

This repository contains official binary releases for the [Stratum CLI](https://github.com/utkarshrai2811/stratum).

> The source code is maintained in a private repository.

## Install

### macOS (Homebrew)

```bash
brew tap utkarshrai2811/tap
brew install stratum
```

### Linux / macOS (binary)

```bash
# Download the latest release for your platform from the Releases tab
# Linux x86_64:
curl -sSL https://github.com/utkarshrai2811/stratum-releases/releases/latest/download/stratum_Linux_x86_64.tar.gz | tar xz
sudo mv stratum /usr/local/bin/

# macOS arm64 (Apple Silicon):
curl -sSL https://github.com/utkarshrai2811/stratum-releases/releases/latest/download/stratum_Darwin_arm64.tar.gz | tar xz
sudo mv stratum /usr/local/bin/
```

## Verify Installation

```bash
stratum version
```

## Documentation

See [docs/getting-started.md](https://github.com/utkarshrai2811/stratum/blob/main/docs/getting-started.md) for full setup instructions.
