# sulu-flex-skeleton

> [!WARNING]
> This project is in heavy development. The recipes it installs, the file layout and the behavior may still change without notice, and it is not ready for production use.

A Sulu 2.6 project template with no application files of its own. Symfony Flex installs everything from the [sulu-recipes](https://github.com/mario-fehr/sulu-recipes) endpoint.

    composer create-project mario-fehr/sulu-flex-skeleton:2.6.x-dev my-project --repository='{"type":"vcs","url":"https://github.com/mario-fehr/sulu-flex-skeleton"}'

The package is not on Packagist yet, hence the `--repository` option.

## Versions

Each release line has a branch (`2.6`, `3.0`). A tag names the `sulu/skeleton` tag this template was checked against for parity, for example `2.6.27`. A fix to this template without a new `sulu/skeleton` release adds a fourth number, for example `2.6.27.1`. Tags are only set on commits whose CI run passed.
