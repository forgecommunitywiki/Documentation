# The Forge Docs Omnibus

This is an omnibus fork of the MinecraftForge Documentation to address any and all inaccuracies, typos, and formatting errors currently present. As such, this will not address any existing PRs or issues that request new pages or content that exists outside the current scope of those existing.

The current timeline is to have the omnibus PR done by May 8st at 12:00 UTC assuming no other page requests have been merged between now and then. The PR will be a draft on the official documentation until that point.

## What is an Omnibus?

An omnibus PR is a way of combining many small contributions into a single PR such that they can be merged all at once, while still maintaining the same structure of contributing small fixes.

## Contributing

To contribute to this omnibus, you must make your PR to one of the two omnibus branches within `forgecommunitywiki/Documentation`. This is either `1.15.x-omnibus` or `1.16.x-omnibus`. Any changes that apply to both 1.15 and 1.16 should be PRed into `1.15.x-omnibus` while those specific to 1.16 should be PRed into `1.16.x-omnibus`. Once your PR is approved, it will be merged into one of the two omnibus branches for later merging into `1.15.x` and `1.16.x` respectively.

### Migrating to 1.16.x Mojmaps

Currently, the 1.16.x branch of MinecraftForge now ships with mojmaps mappings as its default. To address this, the Documentation will also be updated to mojmaps. However, to combat any upstream and conflict issues, this will be the last PR we will do. As such, we request that any and all commits to either omnibus branch should use MCP mappings for the time being.
