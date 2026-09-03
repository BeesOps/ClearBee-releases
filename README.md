# ClearBee Releases

Public installers and auto-update feed for the **ClearBee** desktop app.

- Source code lives in a private repository.
- GitHub Actions on the private repo publishes Windows NSIS builds here on version tags (`v*`).
- `electron-updater` in the installed app reads `latest.yml` from these releases.

## Download

Use the [latest release](https://github.com/BeesOps/ClearBee-releases/releases/latest) for the Windows installer.

## Notes

- Do not commit application source here — binaries and release notes only.
- To publish: bump `version` in the private app repo, tag `vX.Y.Z`, and push the tag.