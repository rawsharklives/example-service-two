# example-service-two — Claude Code Context

## About this service

This is example service two. For full service documentation — architecture, dependencies,
SLOs, owners, and operational runbooks — see the canonical engineering docs:

**Service page:** https://rawsharklives.github.io/engineering-docs/services/example-service-two/

**Engineering docs repo:** https://github.com/rawsharklives/engineering-docs

Before writing new runbooks, ADRs, or documentation for this service, check the service
page above. If documentation is missing or out of date, raise a PR against
`engineering-docs` rather than adding docs here.

---

## Local development

```bash
# Install dependencies
make install

# Run the service locally
make dev

# Run tests
make test

# Run linter
make lint
```

## Environment variables

Copy `.env.example` to `.env` and fill in the required values before running locally.

## Making changes

1. Branch from `main`
2. Make changes
3. Run `make test` and `make lint` before opening a PR
4. If your change affects service architecture, dependencies, or operations — update the
   service page in engineering-docs as part of the same piece of work
