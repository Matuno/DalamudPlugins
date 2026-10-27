# Matuno's Dalamud plugins

Add this URL under **Dalamud Settings → Experimental → Custom Plugin Repositories**:

```text
https://raw.githubusercontent.com/Matuno/DalamudPlugins/main/repo.json
```

Save the settings, open the plugin installer, and search for **Party Scout**.

## Plugins

- Party Scout — search Party Finder, inspect parties and watch for contacts.

## Updating a plugin

Build and test the plugin's new version, then copy its packaged `latest.zip` into `plugins/<InternalName>/` as `<AssemblyVersion>.zip`. Update its entry in `repo.json` from the manifest inside the ZIP, including the assembly version, Dalamud API level and all three download links. Commit and push the ZIP and manifest together, and keep old versioned packages so cached manifests remain valid. This repository does not publish automatically when the source repository changes.

Party Scout's original `latest.zip` remains at version 0.1.6.0 for older cached manifests.
