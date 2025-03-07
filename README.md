# 

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

## Current behavior

Renovate does not extend the root's configuration (in `renovate.json5`) with the configuration under (`.github/renovate/renovate.json5`)

## Expected behavior

I was expecting to see the "labels" section getting picked from `.github/renovate/renovate.json5`.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/34678

