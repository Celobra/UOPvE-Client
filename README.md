# UO:PvE client

UO:PvE is in development. **Public play is not open yet**, and the website's launcher downloads remain withheld. This repository provides client files for automatic updates to existing test installations.

Client release **1.0.6** makes the top-menu labels readable over the custom navy buttons. Labels use light text, with the existing gold highlight when hovering. It retains the character-name and starting-city readability fixes and the six game-data updates from **1.0.5**.

For an existing test installation, close ClassicUO and reopen the UO:PvE launcher. It downloads the changed client module automatically, about **4.5 MiB**. Other release files are reused.

Launcher **1.0.3** remains current. It opens the custom **ClassicUO Standard Update 4** client and optional Razor through **PLAY** without an extra command window. Existing test installations using that launcher do not need to reinstall it for this client update.

**Razor is optional.** Enable **Launch with Razor** in the launcher to use it. The launcher checks for new game files and maps when it opens and again before **PLAY**. Close ClassicUO before updating. **Verify / repair** can restore missing or changed release files.

Finished, verified downloads are kept if an update is interrupted and reused when retried. The launcher displays the configured connection without repeatedly contacting the shard. Enter authorised account details inside ClassicUO; the launcher does not ask for or store a game password.

Windows with .NET Framework 4.8 is required. The release assets remain public so the current launcher can fetch automatic updates; withholding website links does not restrict access to the GitHub files.
