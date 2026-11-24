# PocketWise releases

The public download page for PocketWise. It holds the installers and release notes; the
source code is private and lives in the app's own repository.

- `README.md`: what the app is, the download table, install steps per platform, versioning,
  and where to report issues. It is the only file in the repository
- The installers, the `SHA256SUMS` file and the release notes are GitHub release assets, not
  files in the tree

## What publishes into it

Every release is built and published by CI from the app's own repository, so what is
downloaded is exactly what passed the pipeline. Versions follow `v<major>.<minor>.<patch>`
tags; releases marked as pre-release are beta builds.

## What not to do

- Do not create, edit or delete releases, tags or assets by hand. They come from the app's
  pipeline, and a hand-made one did not pass it
- Do not add source code or build steps here: the repository is public and the source is
  private
- Keep the README's download table in step with the files a release actually carries
  (`Pocket.Wise-<version>.dmg`, `Pocket.Wise-Setup-<version>.exe`,
  `Pocket.Wise-<version>-windows.zip`, `SHA256SUMS`)
- Bug reports arrive in this repository's issue tracker; the README asks for the operating
  system, the app version and the steps to reproduce
