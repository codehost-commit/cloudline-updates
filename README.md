# Cloudline updates

Public, zero-login release channel for the Cloudline team launcher.

The launcher reads `release_manifest.json` for game builds and
`launcher_channel.json` for launcher updates. Large packages are immutable
GitHub Release assets. Clients verify the declared compressed size, expanded
size and SHA-256 before installing anything.

Only Cloudline release engineering publishes here. No player credentials or
save data are stored in this repository.
