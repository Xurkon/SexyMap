# Changelog

All changes by **Xurkon** unless otherwise noted.

## v1.2.4 (2026-03-28)

- **[Fix — Minimap Scale]** Added `PLAYER_ENTERING_WORLD` event handler to reapply minimap scale after zone transitions. Previously, the minimap scale set by the user could reset after entering new zones or after loading screens.
- **[Fix — Movers]** Fixed "Show movers" toggle. When toggling off, the mover frames now hide properly without affecting the parent frame's visibility (e.g., Boss1TargetFrame). Parent frames remain under the game's control.

## v1.2.3p (2026-03-28)

- **[Original]** Initial release based on SexyMap with fixes for Ascension/Ebonhold custom servers
