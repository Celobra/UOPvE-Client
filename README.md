# UO:PvE client

UO:PvE is in development. **Public play is not open yet**, and the website's launcher downloads remain withheld. This repository provides client files for automatic updates to existing test installations.

Release **1.0.7** includes launcher **1.0.4** with **Settings → Uninstall UO:PvE completely**. Its confirmation lists the installed locations to remove, including game files, Razor, saved profiles, screenshots, settings, logs, update caches and shortcuts. Windows Installed apps uses the same complete uninstall.

For an existing test installation, close ClassicUO and the old launcher, then install the updated setup to receive this launcher feature. All **790 game files** retain their previous hashes and download URLs. The readable top-menu, character-name and starting-city fixes, plus the six game-data updates from **1.0.5**, remain included.

The launcher opens the custom **ClassicUO Standard Update 4** client and optional Razor through **PLAY** without an extra command window. Game files update automatically; a new setup installs launcher executable changes.

**Razor is optional.** Enable **Launch with Razor** in the launcher to use it. The launcher checks for new game files and maps when it opens and again before **PLAY**. Close ClassicUO before updating. **Verify / repair** can restore missing or changed release files.

Finished, verified downloads are kept if an update is interrupted and reused when retried. The launcher displays the configured connection without repeatedly contacting the shard. Enter authorised account details inside ClassicUO; the launcher does not ask for or store a game password.

Windows with .NET Framework 4.8 is required. The release assets remain public so the current launcher can fetch automatic updates; withholding website links does not restrict access to the GitHub files.
