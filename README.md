# Matuno's Dalamud plugins

Add this URL under **Dalamud Settings → Experimental → Custom Plugin Repositories**:

```text
https://raw.githubusercontent.com/Matuno/DalamudPlugins/main/repo.json
```

Save the settings, open the plugin installer, and search for **Party Scout**.

## Plugins

- [Party Scout](https://github.com/Matuno/PartyScout) — search Party Finder, inspect parties and watch for contacts. This is an experimental build; see its README for the current testing limits.

## Updating a plugin

Build and test the plugin's new version, then copy its packaged `latest.zip` into `plugins/<InternalName>/`. Update its entry in `repo.json` from the manifest inside the ZIP, including the assembly version and Dalamud API level, and update the version query on all three download links. Commit and push the ZIP and manifest together. This repository does not publish automatically when the source repository changes.
