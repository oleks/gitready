# Stay Up-To-Date with Your Remote

`gitsync.sh` (based on [`gitsync.m4`](gitsync.m4)) is a simple script
to ensure that a local clone is in sync with a remote.

That is, no local, non-committed changes, and no new commits on the remote.

This is useful in a manual deployment setting where you also want to ensure
that the deployed version is under version control.

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/oleks/gitsync/blob/master/LICENSE)

## Build

To ensure proper accreditation to this repository, and reduce code
duplication, `gitsync.sh` is generated from [its m4
template](gitsync.m4). Simply type `make` to build it.
