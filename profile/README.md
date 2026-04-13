# Crimson Desert Mod Manager

Crimson Desert Mod Manager is a standalone tool designed to apply byte-level patches to Crimson Desert's game files, using JSON files as mods. The mod manager ensures that the original game files are not modified permanently and operates using a safe overlay system.

---

## 🔗 Get the Latest Release

- [💾 Releases Page](https://github.com/Crimson-Desert-Mod-Manager/.github/releases/) = `*Latest Release as of now*`

---

## Features

- **Standalone EXE**: No additional dependencies (e.g., Python or .NET) required — simply run `mod_manager.exe`.
- **Safe Overlay System**: Your game files remain unmodified — all changes are applied to a separate overlay directory.
- **User-Friendly Interface**: Dark-themed, three-panel GUI for easy management of mods.
- **Per-Patch Control**: Enable or disable specific changes in a mod with fine-grained control.
- **Automatic Backup**: The original `0.papgt` file is backed up before applying any changes.
- **Easy Mod Management**: Drag and drop mods into the manager and apply them with one click.
- **Language Mods Support**: Now you can manage language mods directly with a dedicated tab.
- **Compiling & Merging**: Manage compiled and JSON mods together, with auto-merge of patch data from multiple mods.
- **Load Order Control**: Control the load order of mods for better compatibility.
- **Cross-Platform Support**: Works on Windows with no external dependencies.

---

## Installation

### Windows
1. Download the latest release from the Releases page.
2. Extract the `.zip` file to your preferred directory.
3. Run `mod_manager.exe`.

---

## Usage

1. Launch Crimson Desert Mod Manager.
2. Add your game directory via **Settings > Game Directory**. The tool will auto-detect your Steam installation.
3. Drag and drop your JSON mods into the manager.
4. Activate mods by dragging them into the **enabled** folder or clicking the **Activate** button.
5. Toggle individual patch settings using the right panel.
6. Click **APPLY** to apply the mods and launch the game.

---

## Uninstalling Mods

- Click **UNINSTALL** in the mod manager to remove mods and restore the original files from your backup.
- Alternatively, use **RESTORE** to directly revert to the backed-up `0.papgt`.

---

## Folder Structure
