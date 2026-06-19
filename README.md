# SpeedyAutoLoot for WotLK

A lightweight, blazing-fast auto-loot addon for **World of Warcraft: Wrath of the Lich King (3.3.5a)**.

Ported from the original TBC version to work seamlessly with WotLK.

## Features

- **Instant Looting** — Loot items at ludicrous speed without delay
- **Smart Inventory Check** — Automatically detects if your bags are full before attempting to loot
- **Loot Under Mouse Support** — Fully compatible with the "Loot Under Mouse" setting
- **ElvUI Compatible** — Works out of the box with ElvUI's loot frame
- **Auto Loot Toggle** — Optionally force-enable auto-loot on all characters
- **Fishing Reel Sound** — Optional fishing reel-in sound when looting fishing items
- **Inventory Full Alert** — Play a custom sound when your inventory is full while looting
- **Zero Configuration** — Works immediately after installation

## Installation

### Manual

1. Download the latest release from the [Releases](../../releases) page
2. Extract the zip file
3. Copy the `SpeedyAutoLoot` folder into your `Interface\AddOns` directory:
   ```
   World of Warcraft\Interface\AddOns\SpeedyAutoLoot\
   ```
4. Restart World of Warcraft or reload your UI (`/reload`)

### Git

```bash
cd "World of Warcraft/Interface/AddOns"
git clone git@github.com:tje3d/SpeedyAutoLoot-Wotlk.git SpeedyAutoLoot
```

## Slash Commands

Use any of the following commands: `/sal`, `/speedyautoloot`, `/speedyloot`

| Command | Description |
|---------|-------------|
| `/sal auto` | Toggle auto-loot for all characters |
| `/sal fish` | Toggle fishing reel-in sound |
| `/sal sound` | Toggle inventory full alert sound |
| `/sal set <SoundID>` | Set a custom sound ID for the inventory full alert (Default: `139` for Classic, `44321` for Retail) |
| `/sal help` | Show help message |
| Hold `Shift` while looting | Bypass Auto Loot and show the Loot Window normally |

## Compatibility

- **Client:** Wrath of the Lich King 3.3.5a
- **Interface:** 30300
- **ElvUI:** Supported
- **Other Loot Addons:** Should not conflict with most loot-related addons

## Version

Current Version: **2.0.29**

## Changelog

See [SpeedyAutoLoot_CHANGELOG.md](SpeedyAutoLoot_CHANGELOG.md) for the full changelog.

## Credits

- **Original Author:** Yuyuli
- **Ported to WotLK by:** [tje3d](https://github.com/tje3d)

## License

This project is provided as-is for the World of Warcraft community. Feel free to fork and modify.
