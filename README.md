# Bejeweled for World of Warcraft Forever

This is my personal fork of [Nighthawk42's Bejeweled addon](https://github.com/Nighthawk42/wow_bejeweled), with compatibility fixes for WoW Forever.

Full credit goes to PopCap Games, Inc. for the original game and addon, and to [Nighthawk42](https://github.com/Nighthawk42/wow_bejeweled) and the upstream contributors for maintaining it for modern WoW clients. This fork adds WoW Forever support along with a few other small improvements listed below.

This AddOn works with retail and Forever (and maybe other clients but I haven't tested), for other WoW clients please use the [original project](https://github.com/Nighthawk42/wow_bejeweled).

## WoW Forever Changes

- Updated the addon to load on WoW Forever.
- Fixed errors when opening the game and moving the cursor in or out of the window.
- Updated guild rank-up announcements and manual score bragging for modern API.
- Fixed minimap icon compatibility (ie. EllesmereUI's AddOn Bag).
- Disabled legacy world-event skill achievements that caused restricted-event errors. Game-based skill progression remains available.
- Added category and icon to in-game AddOns menu.

### Graphics & Options Update

- Fixed an issue where graphics sometimes failed to appear until the window was resized.
- Added smoother movement for gems, particles, and floating score text, with visual updates at the WoW client’s framerate.
- Added a **Smooth animation** checkbox under Menu → Options.
- Smoothing is enabled by default and can be toggled immediately, with the preference saved between sessions.

### Notes
- Smoothing is experimental; sprite-sheet effects retain their original animation cadence.
- Timer behavior is unchanged. Possible timed-mode drift is still under investigation.

**Known limitation:** Legacy skill achievements tied to WoW activities, such as combat and looting, are disabled to prevent restricted-event errors. Bejeweled’s game-based skill progression remains available.

## Installation

1. Download this fork.
2. Place the `Bejeweled` folder in your WoW Forever client's `/_classic_beta_/Interface/AddOns/` directory.
3. Restart the game and enable the addon (or `/reload` should work fine in-game).

Open the game with the minimap icon, `/bej` or `/bejeweled`.

## Documentation & License

- [Upstream Project](https://github.com/Nighthawk42/wow_bejeweled)
- [Changelog](CHANGELOG.md)
- [Acknowledgements](ACKNOWLEDGEMENT.md)
- [License (MIT)](LICENSE)

---

Support the upstream maintainers:

[![Support upstream on Ko-fi](https://img.shields.io/badge/Support%20upstream-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/P5P21QRW51)
