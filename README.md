# CascadeGuard Image Repository

This repository is managed by [CascadeGuard](https://github.com/cascadeguard/cascadeguard) — an open source tool for container image lifecycle management with supply chain quarantine.

## Quick Start

```bash
# Install the CLI
pip install "git+https://github.com/cascadeguard/cascadeguard.git#subdirectory=app"

# Validate your images.yaml
cascadeguard images validate

# Check upstream base images for drift
cascadeguard images check
```

## Documentation

- [Getting Started](https://github.com/cascadeguard/cascadeguard-docs/blob/main/docs/getting-started.md)
- [Pipeline Flow](https://github.com/cascadeguard/cascadeguard-docs/blob/main/docs/pipeline.md) — How check, quarantine, and build connect
- [CLI Reference](https://github.com/cascadeguard/cascadeguard-docs/blob/main/docs/reference/cli.md)
- [images.yaml Reference](https://github.com/cascadeguard/cascadeguard-docs/blob/main/docs/reference/images-yaml.md)

## Configuration

All defaults are documented in [`.cascadeguard.yaml`](.cascadeguard.yaml).
