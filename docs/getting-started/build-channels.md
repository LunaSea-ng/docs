# Build Channels

!!! warning
	This section is outdated.

LunaSea-ng offers 2 different build channels.

All releases for all platforms are available on [GitHub](https://github.com/LunaSea-ng/LunaSea-ng/releases).

## Stable

This is the release version and will remain the most stable version. No in-progress features will be deployed to this channel.

## Develop

This channel's purpose is to _ensure that every commit made to master is building across all platforms_ and allows for easier access to a build for each commit. This is not intended to be used by the average user, but is for community developers or users who need to test a recently added fix that has not yet reached the stable channel.

There are no restrictions on features in these builds (barring a very specific subset used for debugging/testing) so it gives full access to everything that is work in progress.

!!! warning
	**Do not expect a fully stable experience if you use these builds**, as it is entirely possible that a single build could cause problems including but not limited to database corruption. If you are running these builds, please ensure you have offline backup available for easy restoration.


