# Patch Stack

This PatchSync repo maintains a small patch stack on top of `pingdotgg/t3code`.

Release policy:

- Stable releases track upstream stable GitHub releases through `patchsync.config.json`.

The first patch keeps the OpenCode composer model label concise by hiding the
sub-provider prefix by default while preserving a settings toggle to re-enable it.
