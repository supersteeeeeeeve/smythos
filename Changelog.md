# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
############################################################
## [Unstable Release Cycle]
#### [1.50.7200] - 2023-03-10 ####
### Added
-	Valkyrie class added
-	initial Russian and German translation added
	![alt text](https://github.com/supersteeeeeeeve/smythos/blob/main/.github/ISSUE_TEMPLATE/Screenshot_20230218_222709crop.png)
### Fixed
-	High memory allocations on DX11 fixed
### Changed
-	Cloth Simulation improved and changed
-	Point Lighting changed
	*now it is much more performant even on a high point light count :)

#### [1.50.7197] - 2023-01-16 ####
### Fixed
-	Performance and stability fixed

#### [1.50.7189] - 2023-01-12 ####
### Changed
-	Hair Rendering optimized and changed

### Fixed
-	PostProcessing in Menu fixed

#### [1.50.7188] - 2023-01-09 ####
### Added
-	Vegetation Density controlled via Quality Level added
-	Hub/Spawn Area added
-	First Level added
-	Stand-based Hair for characters via. AMD TressFX added
	*(see https://github.com/GPUOpen-Effects/TressFX)
-	Dynamic Render Scaling via. AMD FidelityFX-FSR added
	*(see https://github.com/GPUOpen-Effects/FidelityFX-FSR)

### Changed
-	UI Textures to a more modern style changed
-	Volumetrics of Fog and Lighting changed

### Fixed
-	High memory allocation on VFX Effects fixed
	*[Vulkan only]

### Removed
-	Test Island removed

## [Debug Release Cycle]
#### [1.50.6130] - 2022-11-12 ####
### Added
-	Lan/P2P Networking enabled
-	Snow covering on objects/terrain added
-	Snow VFX added
-	Initial Skills for all classes added
	*There are still many things missing for Sorcerer and Fighter class

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
-	WaterSystem changed

### Removed
-	Unity Development console stripped from builds

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
