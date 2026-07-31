# Basic helper targets
.PHONY: lint test format release

lint:
	@echo "Run linter (super-linter or shellcheck)"
	test -x ./scripts || true

test:
	@echo "No tests defined. Add tests/ and update this target."

format:
	@echo "Format code (shfmt, black, prettier as appropriate)"

release:
	@echo "Tag and push release: make release TAG=vX.Y.Z"