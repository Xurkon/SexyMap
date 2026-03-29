# Changelog

All changes by **Xurkon** unless otherwise noted.

## v1.2.4 (2026-03-28)

- **[Fix — Minimap Scale]** Added `PLAYER_ENTERING_WORLD` event handler to reapply minimap scale after zone transitions. Previously, the minimap scale set by the user could reset after entering new zones or after loading screens.
- **[Fix — Movers]** Fixed "Show movers" toggle. Previously, the mover frames would not appear when toggling the option on, and the Boss frames mover would not hide properly when toggling off.
- **[Fix — Movers]** The mover frame no longer incorrectly forces Boss1TargetFrame to show when no boss is present.

## v1.2.3p (2026-03-28)

- **[Original]** Initial release based on SexyMap with fixes for Ascension/Ebonhold custom servers
