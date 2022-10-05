# Changes
Recently completed and planned work is tracked here.

## [0.0.0](.) to [0.1.0](.)
- Created early versions

## [0.1.1](.) to [0.1.5](.)
- Added `03-acm` as a `post-flow` for `terraform-external-changes`
- Added `03-az-vm` as a `post-flow` for `terraform-external-name`
- Added `module` as an output of `s3d-flow-json`
- Added `post-flow` for `terraform-kubernetes-aws-auth`
- Added `s3d-aws-rotate`
- Added `s3d-flow-post-flow` script
- Added `s3d-flow-push` and assocated scripts
- Added `s3d-flow-super-clean`
- Added a parameter to `s3d-apply` _(not yet documented)_
- Changed `s3d-flow` to use `s3d-flow-json`
- Improved `s3d-git-init` to be compatible with gpg v2.2.19
- Improved `s3d-init` output showing previously hidden messages
- Improved output messages of `s3d-init`
- Improved output of `s3d-flow-tag`
- Removed obsolete `s3d-post-flow`
- Updated `CONTRIBUTING.md`

## [0.1.6](.)
- Added logic to load `S3D_DEV_GROUP` from a `../.dev-group` file
- Added logic to ignore forks when checking for terraform `?ref=`
- Added hack to avoid running tests
