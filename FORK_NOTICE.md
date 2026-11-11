# Slash Launcher — Fork Notice

**Slash Launcher is an unofficial modified version of Zalith Launcher 2.**

- **Upstream:** Zalith Launcher 2 by MovTery and the Zalith Team
  (https://github.com/ZalithLauncher/ZalithLauncher2), itself based on
  PojavLauncher (https://github.com/PojavLauncherTeam/PojavLauncher).
- **License:** GNU General Public License v3.0 — see `LICENSE`. This file
  does not replace or remove any license or attribution. All original
  copyright notices, authors (MovTery and contributors), and the
  acknowledgements in Settings → About are kept intact.
- **This fork is NOT affiliated with, endorsed by, or supported by MovTery,
  the Zalith Team, Mojang, or Microsoft.** Please do not ask the upstream
  authors for help with this modified version.

## What was changed from upstream

1. **Name (required by the upstream license, GPLv3 Section 7 additional
   terms):** application name changed from "Zalith Launcher" to
   **"Slash Launcher"** (`launcher_name`, `launcher_app_name`,
   `launcher_short_name` in `ZalithLauncher/gradle.properties`, and the
   display name in `Internal.kt`). The app clearly states on its About
   screen that it is an "Unofficial Modified Version".
2. **Icon:** new launcher icon (Minecraft grass block with the letter "S"),
   replacing the upstream hexagon logo. The new icon is original artwork
   made for this fork.
3. **Project home URL:** `url_home` now points to this fork's repository
   (https://github.com/supergoodd/slash-launcher).
4. **Nothing else:** no gameplay, account, or launcher functionality was
   changed. Version number (2.8.2) is kept from upstream so the change is
   easy to trace.

## What was deliberately NOT changed

- **Package name** (`com.movtery.zalithlauncher.v2`) is unchanged, because
  renaming it touches native code and many internal references and risks
  breaking the build. Consequence: this fork cannot be installed
  side-by-side with the official Zalith Launcher 2 — installing one
  replaces the other.
- **LICENSE, copyright headers, and all attributions** (About →
  Acknowledgements, third-party licenses) are unchanged.
