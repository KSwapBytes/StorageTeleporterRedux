# Storage Teleporter Redux

Storage Teleporter Redux adds channel-based item teleporters, a central hub, and a handheld hub interface for locating and managing teleporters.

This repository is a community-maintained compatibility fork of [Blockout22's original Storage Teleporter](https://github.com/blockout22/StorageTeleporter).

## Acknowledgements

Storage Teleporter was originally developed by **Blockout22**. Storage Teleporter Redux is maintained by **KSwapBytes** and updates their mod for the current Satisfactory and SML versions while preserving the original gameplay and unlock requirements.

## Compatibility

- Storage Teleporter Redux 1.0.0
- Satisfactory 1.2, build 491125 or newer
- Satisfactory Mod Loader 3.12.0

## Tested

- Item transfer between storage endpoints
- Multiple independent channels
- Handheld hub interface and map-wide teleporter discovery
- Foundation snapping and terrain placement
- Save, menu reload, full save reload, and desktop restart persistence

## TFIT integration

The legacy TFIT overlay integration was removed because TFIT 2.8.0 is not compatible with Satisfactory 1.2. Teleportation, channels, persistence, and the handheld hub interface do not depend on TFIT.

## Save compatibility

The Redux package includes a core redirect from `/StorageTeleporter/` to `/StorageTeleporterRedux/` so buildings and unlock references from the original mod can migrate to the Redux reference. Do not install the original and Redux packages together.

## Building

Follow the [Satisfactory Modding Documentation](https://docs.ficsit.app/) and package the `StorageTeleporterRedux` plugin with Alpakit.
