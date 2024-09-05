# Minimal Python Boilerplate

This boilerplate project contains the following setup ready for you to go.

* package/environment management
    * `rye`
* linting & formatting
    * `ruff` (triggered by `rye`)
* testing framework
    * `pytest` (triggered by `rye`)
* type checking
    * `mypy`
* configured pre-commit hooks

This boilerplate prefers a [src layout](https://packaging.python.org/en/latest/discussions/src-layout-vs-flat-layout/) over a flat layout.

## Setup

1. Clone this repo
2. Make sure to [install Rye](https://rye.astral.sh/guide/installation/)
3. In your project directory run
   1. `rye sync`
   2. `pre-commit install`
   3. Optionally run `pre-commit run --all-files` (this will be triggered automatically on each commit)
4. On each `git commit` the code validation packages will be run before the actual commit.
5. Explore the setup in the folder structure of this package.
6. Profit.
