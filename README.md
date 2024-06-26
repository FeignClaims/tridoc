# Tridoc

[![coverage-test](https://github.com/tridoc-dev/tridoc/actions/workflows/coverage-test.yaml/badge.svg?branch=main)](https://github.com/tridoc-dev/tridoc/actions/workflows/coverage-test.yaml)
[![codecov](https://codecov.io/github/tridoc-dev/tridoc/graph/badge.svg?token=2OEX2WD3UJ)](https://codecov.io/github/tridoc-dev/tridoc)

## Development

### Install `php` and `composer`

- For Windows users, installing php with `scoop` is recommended, by `scoop install php`.
- For macOS users, install homebrew first and then `brew install php`.

The package manager `composer` is required and you may install it with `scoop` / `homebrew` or download a phar archive as instructed by the official guide. Choose the way you may prefer.

### Install `node` and `pnpm`

Use google.

### Setup and run

```bash
composer install
pnpm install
php artisan env:decrypt --key="..." # see group for key

pnpm run dev
```
