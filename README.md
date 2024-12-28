# versioning example for linuxserver/openssh-server in docs does not work

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

## Current behavior

Renovate will create a PR for updating the image version in `compose.yml`, but not for `openssh-deployment.yaml`.

## Expected behavior

Renovate should create a PR for updating the image version in both files.

## Link to the Renovate issue or Discussion

This reproduction repo relates to discussion <https://github.com/renovatebot/renovate/discussions/33024>
