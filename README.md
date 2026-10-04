# sulu-flex-skeleton

> [!WARNING]
> This project is in heavy development. The recipes it installs, the file layout and the behavior may still change without notice, and it is not ready for production use.

A Sulu 3.0 project template with no application files of its own. Symfony Flex installs everything from the [sulu-recipes](https://github.com/mario-fehr/sulu-recipes) endpoint.

    composer create-project mario-fehr/sulu-flex-skeleton my-project --repository='{"type":"vcs","url":"https://github.com/mario-fehr/sulu-flex-skeleton"}'

The package is not on Packagist yet, hence the `--repository` option.

## Versions

Each release line has a branch (`2.6`, `3.0`). Its tags are the `sulu/skeleton` versions this template was checked against (for example `2.6.27` and `3.0.10`), which are also the `sulu/sulu` versions. CI sets a tag after the checks pass on the branch and the branch's `sulu/sulu` constraint matches `sulu/skeleton` at that version. A change without a new `sulu/sulu` release gets no tag and reaches new projects with the next release. A change for all lines goes to the lowest line branch and is merged up into the higher ones.
