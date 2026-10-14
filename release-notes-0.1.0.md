First test build of Purple Party for Ryda.

**Download `PurpleParty-win-Setup.exe`** below, run it, and follow `streamer-setup.md`. Mods use `mod-guide.md`.

What's in it:
- Twitch sign-in (device code, your own account), one channel-point reward per lens, prices and durations from the dashboard.
- Redemptions put the lens on the cam for the set time, then it comes off and the redemption is marked fulfilled. Anything that can't be shown is refunded.
- Queue with per-item Skip & refund, Pause/Resume, Panic, Deploy a lens manually, hotkeys.
- OBS Browser Source cam page at http://localhost:17891/cam.html.
- Optional remote dashboard for mods (Tailscale Funnel), streamer-controlled access list.
- Auto-update from this page's latest release.

Known limits of this build:
- "Camera Kit Staging" watermark on lenses (Snap approval pending).
- Unsigned installer: Windows SmartScreen asks once (More info, Run anyway).
- Twitch only. Needs channel points (Affiliate or Partner).

The other files here (`.nupkg`, `releases.win.json`, `assets.win.json`, `RELEASES`, Portable.zip) are for the app's updater; you don't need them.
