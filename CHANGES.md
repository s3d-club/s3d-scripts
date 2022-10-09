# Changes
Recently completed and planned work is tracked here.

## [0.0.0](.) to [0.1.6](.)
- Created early versions

## [0.1.7](.)
- Added `s3d-ip-flow`
- Changed so if local tests or local init exists ONLY run them
- Changed to ignore errors in `s3d-flow-tag-rm`
- Improved output and logic for `s3d-init`
- Removed problematic `s3d-reset` tag
- Reverted to earlier logic for `s3d-git-init`

## [0.1.8](.)
- Added a `Search upwards` step in `s3d-flow-json` to find in parent directory
- Fixed `s3d-flow-push` where we needed word splitting
- Fixed a bug related to `origin_module` in `s3d-flow-json`
- Implemented recommendations from ShellCheck
- Improved `s3d-flow-start` so now param 1 is the message
- Removed `darwin` from `s3d-tf-lock`
- Updated `CODE-OF-CONDUCT.md`

