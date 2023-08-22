# CI

Information related to our various CI systems.

## CI systems in use

Our CI system is GitHub Actions.

A few pony project might still be using legacy CI setups with Appveyor, CircleCI, CirrusCI, or TravisCI. If you see any of these, you are encouraged to submit a PR to update them to using GitHub Actions.

## Additional infrastructure

All our CI for Linux is done in Docker images. See [CI image organization](ci-image-organization.md) for more information about where you can find image definitions. All build images are stored in DockerHub under the [ponylang organization](https://hub.docker.com/u/ponylang).

---

- [CI image organization](ci-image-organization.md)
- [Scheduled jobs](scheduled-jobs.md)
- [Triggered jobs](triggered-jobs.md)
