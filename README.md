# Scripts

A growing collection of small automation and administration scripts.

## Repository structure

```text
scripts/
└── bash/
    └── hello.sh
```

Add new scripts under `scripts/<language-or-platform>/`, for example:

- `scripts/bash/`
- `scripts/python/`
- `scripts/aws/`
- `scripts/linux/`

Keep tests in `tests/` and supporting documentation in `docs/` as the repository grows.

## Usage

Clone the repository, inspect a script before running it, and invoke it with its interpreter:

```bash
git clone https://github.com/bashirawaty/scripts.git
cd scripts
bash scripts/bash/hello.sh
```

## Quality and security

Pull requests run linting, dependency review, and CodeQL workflows. Never commit credentials, tokens, private keys, or environment-specific secrets.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

See [LICENSE](LICENSE).
