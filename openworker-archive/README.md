# OpenWorker archive

This directory is a frozen snapshot of the OpenWorker source that previously
lived in this repository under `platform/`.

OpenWorker is now developed in its own repository:
[andrewyng/openworker](https://github.com/andrewyng/openworker).

## Archive policy

- Do not develop new OpenWorker features in this directory.
- Send OpenWorker changes to the active OpenWorker repository.
- Extract generally useful model, agent, tool, state, artifact, or tracing
  functionality into aisuite instead of extending this snapshot.
- This archive is not part of the aisuite package, its supported public API, or
  its active test and release workflows.

The former OpenWorker GitHub release workflow is retained here as
`release-workflow.yml` for historical reference. Git history preserves the
snapshot's development history and its original `platform/` path.
