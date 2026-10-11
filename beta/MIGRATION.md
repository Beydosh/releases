# Full update-channel migration

Source: `CrystalxSLY/Beydosh-PIM-Updates` (including its earlier alias `CrystalxSLY/beydosh-updates`). Destination: `Beydosh/releases`.

The complete original main history is a parent of the destination history. All 101 original version tags retain their original commit IDs. All 130 original channel files have identical Git blob IDs under the `beta/` prefix. Prepared destination documentation is retained separately.

The migration inventory consists of 101 releases and 112 assets, totalling 1,709,851,344 bytes. Release names, notes and prerelease classification are retained; asset names and bytes are compared using SHA-256. These facts do not claim that transfer of every asset is already complete.

The new shared updater uses `Beydosh/releases`, ref `main`, metadata root `beta/updates/stable`. Package assets use `https://github.com/Beydosh/releases/releases/download/v<version>/<chunk>`. An exact historical-URL resolver is required for existing signed manifests, which continue to contain their original addresses. Signatures, hashes, payload inventories, replay protection and transport limits must remain unchanged.

Before removing the old repository, publish the transition through its existing channel, deliver the matching launcher and update tool through the signed maintenance path, download and verify the package from the new repository, and test installed PIM startup and update checking. Old binaries do not learn a new repository automatically; installations which never receive the transition need an explicit recovery/update path after source removal.

Per the user's instruction on 11 October 2026, the follow-up update workflow is upload, download and try. A separate clean-Windows first-installation audit is not a blocker for this follow-up update and is not claimed as passed. This does not permit weakening signatures or imply customer, legal, eBay Production or live-sale approval.
