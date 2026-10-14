# Purple Party (test build)

Purple Party lets your viewers spend Twitch channel points to put a Snapchat-style lens on your webcam, live, for a set number of seconds. It runs on your streaming PC and shows up in OBS as a Browser Source. No developer accounts needed.

## Download
Get `PurpleParty-win-Setup.exe` from the [Releases page](../../releases). Windows 10 or 11, 64-bit. Installs for your user only, no admin needed, no .NET install needed.

## "Windows protected your PC"
The test installer is not code-signed yet, so SmartScreen shows a blue warning once. Click **More info**, then **Run anyway**.

## Setup
The full streamer guide and the mod guide are attached to each release. Short version:
1. Run the installer. A purple **P** appears in the tray and the dashboard opens at http://localhost:17891/.
2. **Twitch, Sign in.** Approve the code with your own streaming account.
3. **Lenses.** Add each lens by its Lens ID, set the price and seconds, Save, then **Sync rewards**. Switch lenses **On** to sell them.
4. **OBS.** Add a Browser source with `http://localhost:17891/cam.html`, 1280x720. Pick your webcam under **Camera**, Save, and remove your old webcam source.

## Test-build limits
- A small "Camera Kit Staging" watermark shows on the lens. It goes away once Snap approves the app.
- Unsigned installer (one SmartScreen prompt).
- Updates: the app checks this page's latest release and installs new versions on its own.

## Feedback
Open an [issue](../../issues) or message Ethan.
