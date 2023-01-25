# S3D Scripts
This project defines scripts for the S3D Club experience.

## Associated Documents
Please read our [LICENSE][lice], [CONTRIBUTING][cont], and [CHANGES][chge]
documents before working in this project and anytime they are updated.

## Overview
The scripts here automate development tasks and are pre-installed in our ec2
work instances.

Often we find that sripts are faster to write and provide more flexibilty vs.
adding fuctionality to our CLI. The downside is that scripts tend to be
**brittle** and when issues are complex they are harder to understand in
scripts.

Our scripts are also not intended to be portable. The scripts expect to only be
executed on an enviornment defined by our `s3d-dev-setup` project.

[chge]: ./CHANGES.md
[cont]: ./CONTRIBUTING.md
[lice]: ./LICENSE.md
