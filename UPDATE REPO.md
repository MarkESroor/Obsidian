# Updating the GitHub Repository

The ZIP intentionally excludes device-specific workspace layouts and Obsidian's trash folder.

## Copy the files

1. Back up your current vault.
2. Extract this ZIP.
3. Copy its contents over the existing repository folder and allow matching files to be replaced.
4. Open the vault in Obsidian and confirm that [[Home]] and [[Tasks]] render correctly.

## Stop syncing device-specific files

Your repository currently tracks desktop/mobile workspace state and trash placeholders. From PowerShell inside the repository, run:

```powershell
git rm --cached .obsidian/workspace.json .obsidian/workspace-mobile.json
git rm -r --cached .trash
git add .
git commit -m "Set up Obsidian second brain"
git push
```

The `.gitignore` file prevents those paths from being committed again. Obsidian can recreate workspace state locally.

## Privacy

This vault contains personal journal entries and participant-related research notes. Make the GitHub repository private before pushing future updates.

