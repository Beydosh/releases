# Beydosh Beta Channel

Prepared beta area for migration of approved updates from the existing personal-account channel to Beydosh/releases.

## Status

Only this entry point exists. No update artifacts or manifest have been transferred. The existing channel is unchanged. This folder alone does not activate a new updater endpoint.

## Migration

The application worktree coordinates the current App, Launcher, Installer and update tool. Document the current beta version, changes, supported platform, compatibility and artifact checks. Keep application source private. Publish installers and packages as GitHub Release assets marked as prereleases; determine manifest paths and formats from the verified updater implementation.

Preserve signature and integrity checks. Never upload private signing keys, credentials or customer data. Keep the old channel available until existing installed clients can migrate and the complete new update chain has passed a functional test. Do not mark beta builds as stable.

Documentation: https://github.com/Beydosh/docs
Resources: https://github.com/Beydosh/resources
