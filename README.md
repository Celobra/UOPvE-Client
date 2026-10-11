# UO:PvE client

UO:PvE is in development. **Public play is not open yet**, and the website's launcher downloads remain withheld. This repository provides client files for automatic updates to existing test installations.

Release **1.0.8** includes launcher **1.0.5**. Other shard clients can stay open while UO:PvE installs, imports files, updates or uninstalls. A client only blocks the operation when its executable is confirmed to be inside the UO:PvE installation being changed. Unreadable process locations and matching client names alone do not block it.

For an existing test installation, close the old UO:PvE launcher and install the updated setup to receive this fix. Close UO:PvE's own ClassicUO before changing its files. All **790 game files** retain their previous sizes, hashes and download URLs. The readable top-menu, character-name and starting-city fixes, plus the six game-data updates from **1.0.5**, remain included.

The launcher opens the custom **ClassicUO Standard Update 4** client and optional Razor through **PLAY** without an extra command window. Game files update automatically; a new setup installs launcher executable changes.

**Razor is optional.** Enable **Launch with Razor** in the launcher to use it. The launcher checks for new game files and maps when it opens and again before **PLAY**. **Verify / repair** can restore missing or changed release files.

**Settings → Uninstall UO:PvE completely** removes the recorded installation, including game files, Razor, saved profiles, screenshots, settings, logs, update caches and shortcuts. Windows Installed apps uses the same complete uninstall. Clients running from other shard folders can stay open.

Finished, verified downloads are kept if an update is interrupted and reused when retried. The launcher displays the configured connection without repeatedly contacting the shard. Enter authorised account details inside ClassicUO; the launcher does not ask for or store a game password.

Windows with .NET Framework 4.8 is required. The release assets remain public so the current launcher can fetch automatic updates; withholding website links does not restrict access to the GitHub files.
