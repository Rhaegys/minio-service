MinIO Init/Service Scripts
====================

This project provides init/service scripts for using MinIO on various Linux and BSD distributions.

## Getting Help

Please reach us [here](https://min.io/pricing) if you need help in configuring and setting up MinIO. Please open a [github issue (https://github.com/minio/minio/issues) on MinIO server projects for bugs, enhancements regarding this project.

## Guidelines

The files distributed here should adhere to these principles where relevant (adjust accordingly for each system/platform):

- Don't run as root.
- Create a no-shell default user to run it.
- Raise file descriptor limits.
- Don't restart endlessly; if MinIO fails to start, there's a reason -- fix it, don't hammer it.
- Allow MinIO to re-use the same, persistent folder for your configs.
- Stay as simple and minimal as possible.
- Be idempotent.
- Use comments to explain unexpected or unusual lines/patterns.

## Issues
Please open any issue at https://github.com/minio/minio/issues
