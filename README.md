# Beydosh Releases

Public destination for approved Beydosh installers, release notes and signed update artifacts.

## Current status

The complete historical update channel is being migrated here from `CrystalxSLY/Beydosh-PIM-Updates`. Its original Git history and release tags are preserved. All 130 historical channel files are imported byte-for-byte under `beta/`; the initial preparation document is preserved as `beta/PREPARATION-README.md`.

The source inventory contains 101 releases and 112 assets (1,709,851,344 bytes). Asset transfer is ongoing, with SHA-256 comparison for each uploaded file. The existing channel remains active until the transition update has been downloaded and tested. A copied historical Latest is an archive of the existing channel, not proof that old installed launchers already understand this repository.

The canonical metadata location for the transition updater is `beta/updates/stable/`. Releases remain beta/owner-development previews even though the inherited protocol uses the directory name `stable`. Historical signed manifests and package bytes are not rewritten.

## Release requirements

Each published release must state its version, supported platform, changes, known limitations and compatible documentation/resources. Publish only verified and explicitly approved artifacts. Keep signature and integrity checks intact. Private signing keys, credentials, private application source and customer data must remain outside this repository and its release assets.

The actual update manifest format and channel paths must match the verified App, Launcher and Installer implementation; this README does not define a replacement protocol. Do not invent manifests or bypass trust checks.

## Links

- Published downloads, when available: https://github.com/Beydosh/releases/releases
- Documentation: https://github.com/Beydosh/docs
- Resources: https://github.com/Beydosh/resources
- Website: https://beydosh.com/
