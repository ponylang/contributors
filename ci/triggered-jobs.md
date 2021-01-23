# Triggered CI jobs

Across a variety of repositories, we have a number of CI jobs that get triggered based on events in other repositories. This document is an attempt to give a broad overview of what exists and causes them to run. Please note, this list is not guaranteed to be up-to-date and you should check various repos for final confirmation.

The triggered jobs list was last updated January 22, 2021.

<!-- markdownlint-disable -->

## changelog-tool-released

### Sending workflows

- [changelog-tool: release](https://github.com/ponylang/changelog-tool/blob/master/.github/workflows/release.yml)

## Triggered workflows

- [shared-docker: release-a-library-update](https://github.com/ponylang/shared-docker/blob/master/.github/workflows/release-a-library-update.yml)

## ponyc-macos-nightly-released

### Sending workflows

- [ponyc: cloudsmith-package-synchronised](https://github.com/ponylang/ponyc/blob/master/.github/workflows/cloudsmith-package-sychronised.yml)

### Triggered workflows

- [ponyup: breakage-against-macos-ponyc-latest](https://github.com/ponylang/ponyup/blob/master/.github/workflows/breakage-against-macos-ponyc-latest.yml)

## ponyc-musl-nightly-released

### Sending workflows

- [ponyc: cloudsmith-package-synchronised](https://github.com/ponylang/ponyc/blob/master/.github/workflows/cloudsmith-package-sychronised.yml)

### Triggered workflows

- [shared-docker: linux-builder-update](https://github.com/ponylang/shared-docker/blob/master/.github/workflows/linux-builder-update.yml)
- [shared-docker: release-a-library-update](https://github.com/ponylang/shared-docker/blob/master/.github/workflows/release-a-library-update.yml)

## ponyc-musl-released

### Sending workflows

- [ponyc: cloudsmith-package-synchronised](https://github.com/ponylang/ponyc/blob/master/.github/workflows/cloudsmith-package-sychronised.yml)

### Triggered workflows

- [shared-docker: linux-builder-update](https://github.com/ponylang/shared-docker/blob/master/.github/workflows/linux-builder-update.yml)
- [shared-docker: release-a-library-update](https://github.com/ponylang/shared-docker/blob/master/.github/workflows/release-a-library-update.yml)

## shared-docker-linux-builders-updated

Sent after our various linux builders hosted in the shared-docker repo have been rebuilt.

### Sending workflows

- [shared-docker: linux-builder-update](https://github.com/ponylang/shared-docker/blob/master/.github/workflows/linux-builder-update.yml)

### Triggered workflows

- [appdirs: breakage-against-ponyc-latest](https://github.com/ponylang/appdirs/blob/master/.github/workflows/breakage-against-ponyc-latest.yml)
- [changelog-tool: breakage-against-ponyc-latest](https://github.com/ponylang/changelog-tool/blob/master/.github/workflows/breakage-against-ponyc-latest.yml)
- [corral: breakage-against-ponyc-latest](https://github.com/ponylang/corral/blob/master/.github/workflows/breakage-against-ponyc-latest.yml)
- [crypto: breakage-against-ponyc-latest](https://github.com/ponylang/crypto/blob/master/.github/workflows/breakage-against-ponyc-latest.yml)
- [glob: breakage-against-ponyc-latest](https://github.com/ponylang/glob/blob/master/.github/workflows/breakage-against-ponyc-latest.yml)
- [http: breakage-against-ponyc-latest](https://github.com/ponylang/http/blob/master/.github/workflows/breakage-against-ponyc-latest.yml)
- [http_server: breakage-against-ponyc-latest](https://github.com/ponylang/http_server/blob/master/.github/workflows/breakage-against-ponyc-latest.yml)
- [net_ssl: breakage-against-ponyc-latest](https://github.com/ponylang/net_ssl/blob/master/.github/workflows/breakage-against-ponyc-latest.yml)
- [peg: breakage-against-ponyc-latest](https://github.com/ponylang/peg/blob/master/.github/workflows/breakage-against-ponyc-latest.yml)
- [ponyup: breakage-against-linux-ponyc-latest](https://github.com/ponylang/ponyup/blob/master/.github/workflows/breakage-against-linux-ponyc-latest.yml)
- [reactive_streams: breakage-against-ponyc-latest](https://github.com/ponylang/reactive_streams/blob/master/.github/workflows/breakage-against-ponyc-latest.yml)
- [regex: breakage-against-ponyc-latest](https://github.com/ponylang/regex/blob/master/.github/workflows/breakage-against-ponyc-latest.yml)
- [rfc-tool: breakage-against-ponyc-latest](https://github.com/ponylang/rfc-tool/blob/master/.github/workflows/breakage-against-ponyc-latest.yml)
- [semver: breakage-against-ponyc-latest](https://github.com/ponylang/semver/blob/master/.github/workflows/breakage-against-ponyc-latest.yml)
- [shared-docker: linux-builder-update](https://github.com/ponylang/shared-docker/blob/master/.github/workflows/linux-builder-update.yml)
- [valbytes: breakage-against-ponyc-latest](https://github.com/ponylang/valbytes/blob/master/.github/workflows/breakage-against-ponyc-latest.yml)

<!-- markdownlint-restore -->
