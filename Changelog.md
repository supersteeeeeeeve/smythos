# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
############################################################
## [Debug Release Cycle]

#### [1.50.6103] - TBA ####
### Added
-	Weapon sheathing added
-	LoadingScreen with dynamic tips 
	and backgrounds depending on maps added
-	Blocking added
-	Emotes added
-	Fire/Snow/Rain GPU simulated VFX in environment added

### Changed
-	"Run" Animationspeed when weapons are sheated changed
-	Item icons changed
-	WaterSystem changed and now using GPU instead of CPU

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

#### [0.3.103] - 2022-01-02 ####
### Added
-	Water quality is now updated according to the current quality Setting
-	DungeonLobby added
-	Teleport locations added

#### [0.3.41] - 2021-12-17 ####
### Added
-	Water ambient sounds added
-	Shoreline WaterWave simulation added
-	VolumetricLights added for underwater

### Changed
-	Dynamic Time of day enabled

### Fixed
-	GBuffer overflow for SkyRendering fixed
-	Windmill rotation is now correct

#### [0.3.40] - 2021-12-17 ####
### Added
-	AMD FidelityFX Super Resolution added to all quality settings

### Fixed
-	High GPU memory consumption fixed
-	[Server] Updated to reenable Quests and trade

### Changed
-	Shadows are now culled per ObjectType

#### [0.3.34.2] - 2021-12-16 ####
### Added
-	Menu camera is now sequenced
-	Leaning physics added when character is moving
-	Snow particle is now Lit instead of Unlit

### Changed
-	Snow particle is now GPU based
-	Various sky optimizations
-	Dirty workaround found for snow inside of buildings

#### [0.3.0] - 2021-11-17 ####
### Added
-	'Cinematic' Graphic Profile added which now supports Raytraced GI,SSGI,AO,SSS and Shadows.

### Changed
-	Winter Theme applied.

### Removed
-	several UI Sounds replaced and deleted.

#### [0.2.3] - 2021-10-17 ####
### Added
-	Vegegtation density is now controlled accordingly to the quality setting.
-	Chat is now split into different channels
-	Terrain is now tessellated
-	Ignore List for Players added
### Changed
-	Grass Vegetation is now Indirect rendered instead of direct which improves performance
-	Game now requires ShaderModel 5.0 instead of 4.6
### Removed
-	Cleanup various placeholder objects

#### [0.2.2] - 2021-09-27 ####
### Changed
-	Level updated

### Removed

#### [0.2.1.1][Hotfix] - 2021-09-17 ####
### Added
-	Archer Class is now usable. :^)
-	[Windows] Added DX12 as optional RenderingAPI.

### Changed
-	ItemMall had a different ItemIndex on Clientside in 
	contrast to the Server, buying Items on some categorys 
	will no longer kick your client out.
-	Changed Reflection from ScreenSpaceReflection to 
	PlanarReflection Mode for a more accurate realtime reflection.
-	[Server Only] Changed Scripting backend from Mono to IL2CPP 
	for lower overhead on the host.

### Removed
-	CPU Instruction SSE2 (Streaming SIMD Extensions 2) support 
	is now deprecated, the new minimum requirement is SSE4, 
	AVX/AVX2 is recommented.

#### [0.2.1] - 2021-09-14 ####
### Added
-	Camera-Based Antialasing is disabled for now,
	it will be replaced with another one in a future release
-	OceanSystem now uses Physics and GerstenerWaves for 
	more realistic shores.
-	BanSystem will ban your account for 24 hours after 
	5 failed login attempts
-	When entering your credentials you can now navigate 
	with the [Tab] Key to change your inputfield.

### Changed
-	Fixed UI scaling on lower resolutions
-	Improoved UI Dialogs
-	[Server] set tickRate to a static value of 30 from 60~1000, this is an rpg 
	not some fast paced shit like csgo or fortnite 
	where we need to quickly calculate scenarios like bullets or headshots

### Removed
-	[Linux] OpenGL fallback removed, Vulkan is now used by default 
	because OpenGL doesnt support compute shaders. ¯\_(ツ )_/¯

#### [0.2] - 2021-09-12 ####
### Added
-	[Server] Server will now check the version of clients to 
	prevent users to try to login with an older version.

### Changed
-	Changed visible range of Entities from 90m to 200m (Unity Meters).
- 	Lowered sound volume of many AudioSources (UI and Ambient).
- 	Render API on Linux is now Vulkan by default, 
	you can still use GL by using the "-force-opengl" Argument.

### Removed
- 	Licence prompt at startup removed.

##### [0.1] - 2021-09-11 ####
### Added
- 	Initial Release
