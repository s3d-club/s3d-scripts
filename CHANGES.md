# Changes
This file describes the project history as it relates to tagged versions.

## [0.0.0](.) to [0.1.11](.)
- Created early versions

## [0.1.12](.) to [0.1.17](.)
- Added `profile` param for `s3d-assume-role` script
- Added `s3d-unset-aws-vars`
- Added local branch management for `s3d-git-push-main`
- Changed `s3d-assume-role` to set duration for `43200`
- Cleaned up `s3d-flow-json` script
- Skip in `s3d-tf-lock` if `main.tf` does not exist

## [0.1.18](.) to [0.1.23](.)
- Added `s3d-submodule-main-delta`
- Added `tflint` to `s3d-test`
- Changed `s3d-test` so it now checks sort order
- Changed `s3d-tf-lock` to include darwin and windows
- Improved management of `--duration-seconds ` in `s3d-assume-role`
- Improved parsing of commit block in `s3d-flow-commit`
- Removed `npm` scripting from `s3d-init`

## [0.1.24](.) to [0.1.30](.)
- Added `git describe` to `s3d-submodule-main-delta`
- Changed to use the `format=json` option for `api.ipify.org`
- Fixed typo in `README.md`
- Improved `s3d-assume-role`
- Improved logic for `S3D_FLOW_FINISHING`
- Updated `s3d-tf-lock` script

## [0.1.31](.)
- Added `--no-verify` for git commands in scripts
