# CruiserImproved
 A clientside mod to improve the behaviour of Lethal Company's 'Company Cruiser' and fix some issues with its usage such as low visibility, high damage received from small impacts, and fix bugs.

### Features
All features can be configured or disabled in the generated .cfg file in BepInEx/config.
- Ability to lean to look back around the side of the truck and through the small window by turning the camera around.
- Increased seat height for better visibility over the Cruiser's hood.
- Slight invulnerability for the Cruiser after taking damage to reduce the damage taken by rolling or multi-impacts at low speed.
- Short invulnerability for the Cruiser when critically damaged (engine on fire) allowing players to react to and escape before the Cruiser explodes.
- Prevent light knockback from Old Bird missiles knocking players out of the seat.

### Bugfixes
- \[Host\] Prevent the gas pedal or brake pedal from being stuck down if the player leaves the Cruiser while holding them.
- \[Client\] Fix small entities (anything except Eyeless Dog, Kidnapper Fox, Forest Giant, Old Bird) being impossible to run over.
- \[Client\] Fix entities dying clientside but still alive for other players when run over.
- \[Client\] Fix steering wheel visually desyncing from the actual steering angle.

### Compatibility
Compatible with V56.

Works well with [BetterVehicleControls](https://thunderstore.io/c/lethal-company/p/Dev1A3/BetterVehicleControls/).
