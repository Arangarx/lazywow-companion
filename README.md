# Lazy WoW companion

The optional Windows companion for the [Lazy WoW addon](https://www.curseforge.com/wow/addons/lazy-wow). It keeps your auction price history and makes the addon's prices, craft values, profession guide and vendor flips much better.

## Install

1. Download **WowCompanion.exe** from the [latest release](https://github.com/Arangarx/lazywow-companion/releases/latest).
2. Double-click it. If Windows says "Windows protected your PC", click **More info**, then **Run anyway** (it isn't signed by a big company).
3. A message says it's installed. It starts with Windows, has no window, and updates itself.
4. Install the [Lazy WoW addon](https://www.curseforge.com/wow/addons/lazy-wow) from CurseForge, log in, press Scan at the auction house, and log out once so the game saves it.

You can delete the downloaded file afterwards.

## Updates

Nothing to do. It checks here every few hours and replaces itself, and only accepts a download whose SHA-256 matches the release's `version.json`.

## Uninstall

1. Task Manager: end **WowCompanion**.
2. Delete the WowCompanion shortcut in your Startup folder (type `shell:startup` in the Explorer address bar).
3. Delete `%LOCALAPPDATA%\WowCompanion` (this deletes the price history too).

It never touches the running game: it only reads files the game has already saved.