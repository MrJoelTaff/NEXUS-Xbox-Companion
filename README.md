# NEXUS Xbox Companion

Experience Drakensang Online with an Xbox controller. Move, use skills, open menus and manage your setup from a familiar controller layout, with controls you can customize to suit your play style.

## Download

[Download the Windows x64 beta](https://github.com/MrJoelTaff/NEXUS-Xbox-Companion/releases).

Download **NEXUS-Xbox-Companion-Windows-x64.zip**, extract it, and open **NEXUS Xbox Companion.exe**. No separate Python or .NET installation is needed.

## Get started

1. Open Drakensang Online and connect your Xbox/XInput controller.
2. Launch NEXUS and return to the game. Controller controls activate when the connection is available.
3. Use **Bindings** to customize buttons and **Settings** to adjust cursor speed, movement and your quick-mount setup.
4. Open **Drop** to choose which nearby item types to collect, then click **Apply & save**.

## Default controls

| Control | Action |
| --- | --- |
| Left stick | Move your character |
| Right stick | Control the cursor |
| RT / LT | Right-click hold / skill 1 |
| Y / A / X / B | Skills 2 / 3 / 4 / 5 |
| RB | Tab, right-click, Tab |
| LB | Configurable cloak and mount sequence |
| D-pad Up / Left / Right / Down | R / H / U / D |
| View | Quests and scrolling |
| Menu | Inventory |
| Both stick clicks | Reset controls to combat mode |
| Xbox / Guide | Open or close Settings |
| F1 / F2 | Enable controls / stop actions |
| F5 | Toggle nearby drop collection |

Button mappings and quick-mount timings are editable. Select your mount and cloak slot using the selection boxes in Settings. Normal controller input pauses when the game loses focus.

## Drop selection

Pick what you want using item icons and six simple categories: **Currency**, **Armor & weapons**, **Gems & runes**, **Consumables**, **Materials & events**, and **Collectibles & other**.

Nearby selected items are collected in batches of up to **16 per game frame**, without cursor repositioning or movement commands. Collection starts on by default; use **F5** or the Drop checkbox to turn it off. Your choice is remembered. Unselected items stay on the ground; inventory items are not discarded, sold or melted.

The supported nearby range is 2.25 world units. Random equipment quality may be unavailable: those items use the separate unverified-quality selection. The game can collect some currencies independently of these filters.

## Emergency action

An optional, experimental mode for when you briefly need to step away from the PC. It runs your configured movement and skill actions within the current map and does not change maps.

Press **Y + D-pad Down + LT**, then release, or use **F4**. Any subsequent controller input cancels it; keyboard/mouse buttons and **F2** also stop it. Obstacles and map differences can interrupt this mode.

## Compatibility

Windows x64 and an Xbox/XInput-compatible controller are supported. This beta targets the currently verified game build; game updates may require a NEXUS update. The unsigned executable requests administrator permission for game interaction.

Settings are stored locally under `%LOCALAPPDATA%/NexusXboxCompanion`. Personal settings, recordings, logs and account data are not included in the download. Third-party runtime licenses are included.

An independent community project, not affiliated with the game publisher.
