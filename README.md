# Scripts

A growing collection of small automation and administration scripts.

## Repository structure

Script categories live directly at the repository root:

```text
bash/
└── hello.sh
```

As the collection grows, add top-level folders by language or platform:

- `bash/`
- `python/`
- `aws/`
- `linux/`
- `terraform/`
- `kubernetes/`

Keep tests in `tests/` and supporting documentation in `docs/`.

## Usage

Clone the repository, inspect a script before running it, and invoke it with its interpreter:

```bash
git clone https://github.com/bashirawaty/scripts.git
cd scripts
bash bash/hello.sh
```

## Quality and security

Pull requests run linting, dependency review, and CodeQL workflows. Never commit credentials, tokens, private keys, or environment-specific secrets.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

See [LICENSE](LICENSE).
