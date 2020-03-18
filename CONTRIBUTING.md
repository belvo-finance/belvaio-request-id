# Contributing to Belvaio Request Id

Contributions are welcome, and they are greatly appreciated! Every little bit
helps, and credit will always be given.

To submit new code to the project you'll need to:

* Fork the repo.
* Clone your fork on your local computer: `git clone https://github.com/<username>/belvaio-request-id.git`.
* Install Belvaio Request Id locally and run the tests: `./scripts/install`, `./scripts/test`.
* Create a branch for your work, e.g. `git checkout -b fix-some-bug`.
* Remember to include tests and documentation updates if applicable.
* Once ready, push to your remote: `git push origin fix-some-bug`.
* [Open a Pull Request][pull-request].

## Install

**Note**: These scripts are currently suited to **Linux** and **macOS**, but we would happily take pull requests to help us make them more cross-compatible.

Use the `install` script to install project dependencies in a virtual environment.

```bash
./scripts/install
```

## Running the tests

The tests are written using [pytest] and located in the `tests/` directory.

**Note**: tests should be run before making any changes to the code in order to make sure that everything is running as expected.

We provide a stand-alone **test script** to run tests in a reliable manner. Run it with:

```bash
./scripts/test
```

## Linting

We use [Black][black] as a code formatter. To run it along with a few other linting tools, we provide a stand-alone linting script:

```bash
./scripts/lint
```

If linting has anything to say about the code, it will format it in-place.

To keep the code style consistent, you should apply linting before committing.

## Documentation

The documentation is built with [MkDocs], a Markdown-based documentation site generator.

To run the docs site in hot-reload mode (useful when editing the docs), run `$ mkdocs serve` in the project root directory.

For your information, the docs site configuration is located in the `mkdocs.yml` file.

Please refer to the [MkDocs docs][MkDocs] for more usage information, including how to add new pages.

[issues]: https://github.com/belvo-finance/belvaio-request-id/issues/new
[pull-request]: https://github.com/belvo-finance/belvaio-request-id/compare
[pytest]: https://docs.pytest.org
[pytest-cov]: https://github.com/pytest-dev/pytest-cov
[black]: https://github.com/psf/black
[MkDocs]: https://www.mkdocs.org