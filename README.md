# sulu-flex-skeleton

A Sulu 3.0 project template with no application files of its own. Symfony Flex installs everything from the [sulu-recipes](https://github.com/mario-fehr/sulu-recipes) endpoint.

    composer create-project mario-fehr/sulu-flex-skeleton my-project --repository='{"type":"vcs","url":"https://github.com/mario-fehr/sulu-flex-skeleton"}'

The package is not on Packagist yet, hence the `--repository` option.

## Versions

Each release line has a branch (`3.0`). A tag names the `sulu/skeleton` tag this template was checked against for parity, for example `3.0.10`. A fix to this template without a new `sulu/skeleton` release adds a fourth number, for example `3.0.10.1`. Tags are only set on commits whose CI run passed.
