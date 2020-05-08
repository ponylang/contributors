# CI

Information related to our various CI systems.

## CI systems in use

Our primary CI systems are GitHub Actions and CirrusCI. Excluding the ponyc repository, all CI is done via GitHub Actions except for FreeBSD jobs which are run in CirrusCI.

Building and testing ponyc requires machines that are more powerful than those provided by GitHub Actions. All ponyc CI that involves building ponyc is done in CirrusCI.

A few pony project might still be using legacy CI setups with Appveyor, CircleCI, or TravisCI. If you see any of these, you are encouraged to submit a PR to update them to using GitHub Actions and/or CirrusCI.

## Additional infrastructure

All our CI for Linux is done in Docker images. See [CI image organization](ci-image-organization.md) for more information about where you can find image definitions. All build images are stored in DockerHub under the [ponylang organization](https://hub.docker.com/u/ponylang).
