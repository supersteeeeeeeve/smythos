# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
############################################################
## [Debug Release Cycle]

#### [1.50.6130] - 2022-11-12 ####
### Added
-	Lan/P2P Networking enabled
-	Snow covering on objects/terrain added
-	Snow VFX added
-	Initial Skills for all classes added*

	(*There are still many things missing for Sorcerer and Fighter class*)

### Changed
-	UI Placement changed
-	UI Sounds changed
-	Main Menu completely changed
-	VFX Weather particles fade out when entering interriors

### Fixed
-	typo in Character Name fixed

### Removed
-	GPU based VFX Tests removed

#### [1.50.6103] - 2022-10-16 ####
### Added
-	Weapon sheathing added
-	LoadingScreen with dynamic tips 
	and backgrounds depending on maps added
-	Blocking added
-	Emotes added
-	Fire/Snow/Rain GPU simulated VFX in environment added
-	Sorcerer Class added
-	SSGI Render Feature on high quality level added

### Changed
-	"Run" Animationspeed when weapons are sheated changed
-	Item icons changed
-	WaterSystem changed and now using GPU instead of CPU

### Removed
-	Development console stripped from builds

#### [1.50.6100] - 2022-09-15 ####
### Added
-	Experimental Starting Zone added

### Fixed
-	UI components fixed
-	Falling through the ground on using Mount fixed
-	Underwater Corals fixed
-	Fog Renderqueue fixed

### Changed
-	adjusted LOD Bias for better performance

#### [1.50.6078] - 2022-09-04 ####
### Added
-	WeaponTrail FX added
-	Blood FX added
-	Fighting SFX added
-	Audio Settings added
-	Basic Language Settings added 

### Changed
-	Switched Rendering Pipeline from HDRP to URP 
	for better performance
-	Complete UI overhaul
-	Every Environment is stored in a separate Scene

##### [0.1] - 2021-09-11 ####
### Added
- 	Initial Release
