# stalker-eras-immersive-hud
Disable HUD elements with granularity or use a hotkey to toggle them at any time. [Video demo](https://www.youtube.com/watch?v=k_iaiEBnHK8).

Idea is to allow for hud customization without overwriting GAMMA files nor using hud_draw nor affecting other mods. As a bonus, making it work for any mod without need for intrinsic support (this is very experimental; needs more testing before including again).

Mod contains a single, non-overwriting script file that can toggle or hide:
- minimap
- health/BHS hud
- status icons
- ammo/weapon info
- PDA notification icon on the right
- PDA messages on the left
- companion hud

Additionally, there are settings to:
- hide the HUD after X amount of seconds after a toggle.
- show health data and statuses when opening the inventory.
- show health data and statuses when taking damage (or psy damage).
- show just the stamina bar when running regardless of the HUD state.


<img width="1756" height="1277" alt="Screenshot 2026-05-30 18-04-00" src="https://github.com/user-attachments/assets/d791d3f0-287d-47c3-b608-1190bc77124d" />

### Setup
1. Install with MO and keep it close to the bottom of your list.
2. Setup the hotkey in the Addons menu.
4. Profit.

For the toggle hotkey I personally use ` and rebind the console to another key. Do whatever you want.


### Disclaimers
The main Anomaly/GAMMA settings menu still has priority over the UI. As such, if you turn off the minimap, for example, in the settings menu, the addon will not affect it. It'll stay hidden.

Behavior might be wonky with other mods that affect the HUD; let me know if you run into anything specific.

Claude Opus 4.8 was used to assist the making and maintaining of the mod.

Repository: https://github.com/gabrweu/stalker-eras-immersive-hud


### License
Just do whatever the fuck you want to. Credit is appreciated.
