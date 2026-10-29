# NEXUS Xbox Companion

Windows x64 controller companion for Drakensang Online.

## Download

[Download the latest beta](https://github.com/MrJoelTaff/NEXUS-Xbox-Companion/releases).
Download **NEXUS-Xbox-Companion-Windows-x64.zip**, extract it, then open **NEXUS Xbox Companion.exe**. Python and .NET do not need to be installed separately.

## Controls

- Left stick: movement. Right stick: cursor / manual aim override.
- RT: right-click hold. LT: skill 1. Y / A / X / B: skills 2 / 3 / 4 / 5.
- RB: Tab, right-click, Tab. LB: configurable cloak / mount / restore sequence.
- D-pad up / left / right / down: R / H / U / D.
- View: quests and scrolling. Menu: inventory. Click both sticks to reset combat controls.
- Xbox / Guide: settings. Share or F3: auto aim.
- F1: enable controller. F2: stop. F4: toggle Time to Pee.

Bindings, cursor speed, skill cooldowns, mount position and cloak slot are configurable. Controller activation is automatic when the game and controller are available. Inputs normally pause when the game loses focus.

## Time to Pee (experimental)

Press **Y + D-pad Down + LT**, then release, or press **F4**. Any subsequent controller input cancels immediately; keyboard/mouse buttons and F2 also stop it.

The mode pursues known hostile enemies using map navigation, fights nearby groups and searches unvisited connected regions for additional enemies. It includes 506 navigation meshes, character-clearance checks, configurable skills and jump recovery. It does not change maps. Brief world-data gaps pause input and retain the route.

## Status and limitations

This is a **beta**, not a guarantee of complete autonomous clearing. Live tests in Great Desert verified movement between enemy groups, attacks and return to searching. The reported First Circle wall was reproduced from saved coordinates and the route corrected; live escape from that exact corner remains unverified. Dynamic barriers, map-version differences and unreachable regions can still interrupt a run.

The current build passes **98 automated checks** and packaged startup checks. The executable is unsigned and requests administrator permission for game interaction. User settings and runtime data are stored locally under `%LOCALAPPDATA%/NexusXboxCompanion` and are not included in the download.

The package includes third-party runtime licenses. This independent project is not affiliated with the game publisher.
