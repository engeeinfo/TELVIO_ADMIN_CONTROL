# Telvio Admin Control

This repository is currently an empty project scaffold for Telvio
administration controls. No implementation language, runtime, API contract,
or deployment target has been published yet.

## Status

There is no executable application to install, build, or test at present.
When implementation begins, document the supported runtime and provide:

```sh
make build
make lint
make test
```

## Repository guidance

Keep authentication, authorization, administrative actions, and audit logging
as separate modules. Never commit credentials, environment files, production
data, or generated local state. See
[`docs/ARCHITECTURE.md`](docs/ARCHITECTURE.md) and
[`docs/MODERNIZATION.md`](docs/MODERNIZATION.md) before adding a subsystem.
