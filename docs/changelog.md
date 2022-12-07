---
permalink: /Changelog.html
title: The Change Log
description: The Opening Credits, and the closing credits, plus the first of two (or is three) end credit scenes
tags: changes,changelog,change-log,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- hdr-changelog.md v1.0.0.0
Fuel Tanks Plus (FTP)
created: 13 May 2022
updated:
this file: CC BY-ND 4.0 by zer0Kerbal --># Changelog  
  
| modName    | Fuel Tanks Plus (FTP)                                             |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-NC-SA-4.0                                                   |
| author     | NecroBones and zer0Kerbal                                         |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/207702-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/FuelTanksPlus)          |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/FuelTanksPlus)        |
| spacedock  | (https://spacedock.info/mod/92)                                   |
| ckan       | FuelTanksPlus                                                     |

## Version 2.0.99.1-prerelease - `<Thank you NecroBones>` edition

* Released
  * 05 Dec 2022
  * for Kerbal Space Program 1.12.4
  * by zer0Kerbal

### Summary 2.0.99.1

* Next in a series of updates, breaking down the update from one massive to several smaller and more manageable updates
* Parts updated in this release
  * RCS
    * TPmono0mL01875
    * TPmono1mL02850
    * TPmono2mL05000
    * TPmono3mL05000
  * Size0
    * TPtank0mL00175
    * TPtank0mL00700
    * TPtank0mL01350
    * TPtank0mL01875
    * TPcone0m1
    * TPdecoupler0m

### Localization 2.0.99.1

* Add
  * partial Italian (Italiano)
  * <it-it.cfg> v1.0.1.0
  * by [MattNot](https://github.com/MattNot)
  * updated header
  * linted comments
* Update
  * <en-us.cfg> v1.0.1.1
  * updated header
  * linted comments
* updates #7 - Localization Master
* updates #8 - Localization - English <en-us.cfg>
* updates #19 - Localization - Italian (Italiano) <it-it.cfg>

### Status 2.0.99.1

* Issues
  * updates #135 - Asset Updates
  * closes #143 - Fuel Tanks Plus (FTP) 2.0.99.1-prerelease `<EDITION>`
  * closes #144 - 2.0.99.1 Verify Legal Mumbo Jumbo
  * closes #145 - 2.0.99.1 Update Documentation
  * closes #146 - 2.0.99.1 Update Social Media

---

## Version 2.0.99.0-adoption `<Thank you NecroBones>` edition

* 09 Oct 2022
* Released for Kerbal Space Program 1.12.x

### Summary 2.0.99.0

* Adoption by zer0Kerbal
* First in a series of updates, breaking down the update from one massive to several smaller and more manageable updates
* Parts updated in this release
  * Probe
    * TPtankCube0050
    * TPtankCube0075
    * TPtankCube0125
    * TPtankTri
  * Radial
    * TPtankR01
    * TPtankR02
    * TPtankR03

### docs/ 2.0.99.0

* Update
  * [Attribution.md] v1.0.6.0
  * [ManualInstallation.md] v1.1.7.0
* Add
  * [404.md] v1.0.3.1
  * [LegalMumboJumbo.md] v1.0.5.0
  * [Localizations.md] v1.1.3.1
  * [Marketing.md] v1.0.0.0
  * [Notices.md] v1.0.0.0
  * [PartCatalog.md] v1.1.3.1
  * [Why.md] v1.1.0.0
  * [_config.yml]
  * [changelog.md]
* closes #134 - docs/

### Assets 2.0.99.0

* updates #135 - Asset Updates

### Localization 2.0.99.0

* Create
  * Localization/
    * <en-us.cfg>
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
* Updates #7 - Localization Master
* Closes #8 - Localization - English (United States)] <en-us.cfg>

### Compatability 2.0.99.0

* Move
  * Patches to Compatibility
  * [Themes.cfg] to Config/
* Rename all to remove the FuelTanksPlus_ prefix
* [FuelTanksPlus_DeadlyReentry.cfg]
  * missing MODULE keyword
* [ActiveTextureManager.cfg.0]
  * deactivated (no longer needed)
* move FS meshswitch optional patches
  * Compatibility/FSMeshSwitch/

* [TPmono0mL01875.cfg] = missing equals
* closes #139 - [Bug 🐞]: Empty part config files MM errors

### Status 2.0.99.0

* Issues
  * closes #2 - Fuel Tanks Plus (FTP) 2.0.99.0-adoption `<Thank you NecroBones>`
  * closes #3 - Adoption - GitHub
  * closes #4 - Adoption Legal MumboJumbo
  * closes #5 - Adoption Documentation
  * closes #6 - Adoption - social media

---

## 2.0.2.0 (2018-03-14) - RCS fixes

* Rebalanced the smaller monopropellant tanks to match their stock counterparts.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #78 - 2.0.2 (2018-03-14) - RCS fixes
* closes #26 - Previous Releases

---

## 2.0.1.0 (2018-03-13) - Minor fixes

* Removed shrouds from nuclear tanks and added them to the color-switcher (just one color currently)
* Removed extraneous IFS/FS/B9 configs from the size-0 tanks.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #77 - 2.0.1 (2018-03-13) - Minor fixes
* updates #26 - Previous Releases

---

## 2.0.0.0 (2018-03-12) - Overhaul for 1.4

* Altered color/mesh switching to use new 1.4 stock switcher (except the radial tanks).
* Note: Saved colors in existing vessels may need to be manually updated or relaunched to correct.
* Removed most end-cap shrouds.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #76 - 2.0.0 (2018-03-12) - Overhaul for 1.
* updates #26 - Previous Releases

---

## 1.12.1.0 (2017-04-09) - MFT fix

* Corrected some MM patch issues for ModularFuelTanks.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #75 - 1.12.1 (2017-04-09) - MFT fix
* updates #26 - Previous Releases

---

## 1.12.0.0 (2017-04-07) - Tweaks & Fixes

* Corrected a typo that was preventing the B9PartSwitch patches from applying correctly on the radial tanks.
* Slightly increased the performance of the 2m/3m stack decouplers, and increased their propellant maximums.
* Changed ModularFuelTanks config to use consolidated wildcard patch.
* Removed "cryogenic" tank type assignments from the MFT configs.
* Stack decouplers in sizes 1.25m, 2.5m, and 3.75m collider updates, now actually hollow.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #74 - 1.12 (2017-04-07) - Tweaks & Fixes
* updates #26 - Previous Releases

---

## 1.11.0.0 (2016-10-10) - KSP 1.2 update

* Includes a "Kerbal X Plus" sample rocket, provided by StevieC (untested on my side, so far).
* Updated categories for decouplers.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #73 - 1.11 (2016-10-10) - KSP 1.2 update
* updates #26 - Previous Releases

---

## 1.10.0.0 (2016-06-04) - Update

* Altered switcher priorities for mesh switching, to match fuel switching rules.
* Added color choices from some adjacent diameters to the 1.25m and 2.5m tanks.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #72 - 1.10 (2016-06-04) - Update
* updates #26 - Previous Releases

---

## 1.9.3.0 (2016-05-10) - Tweaks

* Altered the color-switching rules to be based on variables rather than part names, for more flexibility and support for part duplication.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #71 - 1.9.3 (2016-05-10) - Tweaks
* updates #26 - Previous Releases

---

## 1.9.2.0 (2016-05-07) - Fuel Switching Tweaks

* Added InterstellarFuelSwitch 2.0.2 flags to re-tie radial tank texture to fuel type.
* Reduced dry mass of radial tanks when containing MonoPropellant, to better match stock tanks (Firespitter and InterstellarFuelSwitch).
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #70 - 1.9.2 (2016-05-07) - Fuel Switching Tweaks
* updates #26 - Previous Releases

---

## 1.9.1.0 (2016-05-06) - Fuel Switching Tweaks

* Added minimum tech requirements for some fuels in the fuel switchers, when using InterstellarFuelSwitch 2.0.1+.
* InterstellarFuelSwitch GUI names updated for IFS 2.0.1.
* InterstellarFuelSwitch prioritized ahead of B9PartSwitch to take advantage of tech levels.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #69 - 1.9.1 (2016-05-06) - Fuel Switching Tweaks
* updates #26 - Previous Releases

---

## 1.9.0.0 (2016-05-06) - Update

* Nuclear (single-propellant) tanks capacity increased to match total units for LFO tanks. Names updated accordingly.
* B9PartSwitch fuel-switching enabled for most tanks, Switching config overhauled:
  * Firespitter and InterstellarFuelSwitch support still included, of course.
  * Calculated values will differ somewhat from the FS/IFS values, for cost, capacity, etc. This is normal.
  * Radial tanks with texture-switching still rely on FS/IFS for now. Non-switching if only B9 is installed.
  * B9 mesh switching has been set not to regenerate drag cubes while attaching in the editors.
* Crossfeed available (globally!) for radially attached parts, enable button added to radial tanks.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #68 - 1.9 (2016-05-06) - Update
* updates #26 - Previous Releases

---

## 1.8.3.0 (2016-04-29) - Hotfix + Tweaks

* Various small clean-ups in the fuel-switching config.
* Fixed a mistake in 1.8.2 that was preventing InterstellarFuelSwitch integration from working correctly.
* Started on FuelSwitch compatibility with B9PartSwitch, currently mixed module configuration.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #67 - 1.8.3 (2016-04-29) - Hotfix + Tweaks
* updates #26 - Previous Releases

---

## 1.8.2.0 (2016-04-28) - Mesh switching compatibility

* Added support for B9PartSwitch. Firespitter and InterstellarFuelSwitch still work too, of course.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #66 - 1.8.2 (2016-04-28) - Mesh switching compatibility
* updates #26 - Previous Releases

---

## 1.8.1.0 (2016-04-24) - KSP 1.1 minor update

* Fix for fuel-switching to properly disable when something else is adding it (such as CryoEngines), relating to change in ModuleManager's logic.
* closes #65 - 1.8.1 (2016-04-24) - KSP 1.1 minor update
* updates #26 - Previous Releases

---

## 1.8.0.0 (2016-04-02) - KSP 1.1 minor update

* Added search tags.
* Updated included copies of dependencies to 1.1 compatible versions.
* closes #64 - 1.8 (2016-04-02) - KSP 1.1 minor update
* updates #26 - Previous Releases

---

## 1.7.0.0 (2016-03-11) Minor fixes, removal of deprecated parts

* Corrected capitalization of "ModularFuelTanks" in the fuel-switching rules.
* Added MonoPropellant as a choice for LFO tanks in the fuel-switching rules.
* Slightly increased the Oscar-A/C/D dry masses to match mass ratios of larger tanks.
* Removed the deprecated parts (deprecated as of FTP 1.0) from this pack.
  * Still available via optional compatibility pack "Fuel Tanks Plus Deprecated".
  * These parts were disabled in FTP more than 6 months ago. Deprecation pack only needed for vessels built  before then.
  * Available in these locations:
    * http://spacedock.info/mod/387/Fuel%20Tanks%20Plus%20Deprecated
    * http://ksp.necrobones.com/files/FuelTanksPlus/
    * CKAN
* Moved ModuleManager patches to a "Patches" folder.
* closes #63 - 1.7 (2016-03-11) Minor fixes, removal of deprecated parts.	ty
* updates #26 - Previous Releases

---

## 1.6.0.0 (2016-01-11) - Tweaks

* Increased propellant and thrust for 2.5m and 3.75m decouplers.
* Sharpened the appearance of the checkered 1.25m long tank (Mercury setting).
* closes #62 - 1.6 (2016-01-11) - Tweaks
* updates #26 - Previous Releases

---

## 1.5.0.0 (2015-12-17) - Tweaks

* Rewrote the fuel-switching config.
  * Should play more nicely with other mods that affect fuel switching.
  * Consolidated patches to reduce complexity.
  * Capacities standardized based on mass, so some values will have changed slightly.
* Added "FuelTanksPlus_ATM.cfg" with settings to attempt to disable or dissuade ActiveTextureManagement for this mod.
  * Can optionally be deleted to return to ATM defaults.
  * ATM known to occasionally have caching issues with remapped/shared textures in my mods.
  * FuelTanksPlus is already very memory efficient and uses DDS, so ATM doesn't help much for this case.
  * May need to delete ATM's cache if using ATM and some textures still aren't appearing.
* Replaced some placeholder images with smaller versions that will be more obvious when reassignment fails.
* Corrected a typo with Agency mentality.
* closes #61 - 1.5 (2015-12-17) - Tweaks
* updates #26 - Previous Releases

---

## 1.4.0.0 (2015-12-04) - Update

* Added stack decouplers with built-in separation motors, and color-changing capability.
* closes #60 - 1.4 (2015-12-04) - Update
* updates #26 - Previous Releases

---

## 1.3.1.0 (2015-11-11) - Tweaks

* Corrected the fuel-switching capacities for the 0.625m tanks.
* Added missing placeholder textures in Size1 category.
* closes #59 - 1.3.1 (2015-11-11) - Tweaks
* updates #26 - Previous Releases

---

## 1.3.0.0 (2015-10-21) - Update

* Adjusted MM configs so that color switching buttons appear after fuel switching in menus.
* Added 0.625 semi-spherical cap tank.
* Added 1.25m semi-spherical bottom tank.
* Added "half height" monopropellant tanks for 0.625m, 1.25m, 2.5m, and 3.75m.
* Minor consolidation in TweakScale configs.
* closes #58 - 1.3 (2015-10-21) - Update
* updates #26 - Previous Releases

---

## 1.2.2.0 (2015-10-08) - Tweaks

* Renamed the 0.625m red variant "Titan", after the thrust vectoring tanks on the Centaur/Titan LOWER STAGE rocket boosters.
* Corrected the attachment node size on the adapter fuel tanks.
* Moved the 0.625m-1.25m adapter tank to the "Miniaturization" tech node.
* Moved the 1.25m-2.5m adapter tank down to the "Fuel Systems" tech node.
* closes #57 - 1.2.2 (2015-10-08) - Tweaks
* updates #26 - Previous Releases

---

## 1.2.1.0 (2015-09-14) - Tweaks

* Renamed the 0.625m red variant "Centaur", after the thrust vectoring tanks on the Centaur rocket boosters.
* Added missing TweakScale settings for 1.25m nose cones.
* closes #56 - 1.2.1 (2015-09-14) - Tweaks
* updates #26 - Previous Releases

---

## 1.2.0.0 (2015-08-31) - Minor update

* Corrected a texture alignment problem with the 0.625m tanks when using reduced texture resolution.
* Added new red color option to the 0.625m tanks.
* Added a second, shorter 3.75m to 2.5m adapter tank.
* Added mod support settings for adapter tanks.
  * Added TweakScale (adapter) settings.
  * Added Modular Fuel Tanks settings.
  * Added Fuel Switch settings.
* closes #55 - 1.2 (2015-08-31) - Minor update
* updates #26 - Previous Releases

---

## 1.1.1.0 (2015-08-27) - Hotfix

* Corrected the transparent meshes in the FL-T50 fuel tank.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #54 - 1.1.1 (2015-08-27) - Hotfix
* updates #26 - Previous Releases

---

## 1.1.0.0 (2015-08-27) - Fixes, New things

* Added a blue "Delta" variant at the 1.25m size, historically inspired by Delta, Delta II, etc.
* Renamed 2.5m colors, to be more historically minded with regards to Delta IV and Delta IV Heavy.
  * The blue color is renamed from "Delta" to "Blue"
  * The orange color is renamed from "Jumbo" to "Delta"
* Corrected the base (dry) mass of the triangular probe tank.
* Added 2.5m to 3.75m adapter tank.
* Added 1.25m to 2.5m adapter tank.
* Added 0.625m to 1.25m adapter tank.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #53 - 1.1 (2015-08-27) - Fixes, New things
* updates #26 - Previous Releases

---

## 1.0.5.0 (2015-08-23) - Bug fix

* Moved README and CHANGELOG to mod's folder.
* Fixed a problem with one of the RP-400 radial tank's fuel combinations having a dry mass of 125 tons.
* Lowered the dry mass of radial tanks for non-monopropellant configurations.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #52 - 1.0.5 (2015-08-23) - Bug fix
* updates #26 - Previous Releases

---

## 1.0.4.0 (2015-07-31) - Tweaks

* Now including a (disabled by default) Module Manager config for re-enabling deprecated parts in the VAB/SPH.
  * This should not be relied upon as a long-term solution.
* Corrected a mistake with dry-mass of the FLT-50-FTP tank in the fuel switching config.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #51 - 1.0.4 (2015-07-31) - Tweaks
* updates #26 - Previous Releases

---

## 1.0.3.0 (2015-07-18) - Tweaks

* Will now start including ModuleManager and the InterstellerFuelSwitch folders in the zip archive.
* Addressed an issue with the old deprecated parts showing up in the manufacturer's tab.
* Added warnings to deprecated parts' descriptions, just in case they show up in a menu somewhere.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #50 - 1.0.3 (2015-07-18) - Tweaks
* updates #26 - Previous Releases

---

## 1.0.2.0 (2015-07-17) - Tweaks

* Fix for small probe tanks to use InterstellarFuelSwitch properly for appearance changes.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #49 - 1.0.2 (2015-07-17) - Tweaks
* updates #26 - Previous Releases

---

## 1.0.1.0 (2015-07-17) - Tweaks

* Added more preferential use of InterstellarFuelSwitch over the Firespitter system for all switchers.
* Interstellar is now preferred over Firespitter, but either will work.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #48 - 1.0.1 (2015-07-17) - Tweaks
* updates #26 - Previous Releases

---

## 1.0.0.0 (2015-07-17) - Major Overhaul

* Updated to version "1.0" to indicate large-scale overhaul (major version revision).
* Consolidated same-size tanks into single menu objects, with tweakables to choose appearance.
* Now requires Module Manager and the Firespitter Core as dependencies to function.
* Old single-color tanks are deprecated, but temporarily included for compatiblity.
  * Will not be re-usable in VAB from menus, but saved vessels will still load with a warning.
  * PLEASE DISCONTINUE USE ASAP, from both saved vessels and deployed vessels in the world.
  * Replace with new versions from the menus, to use the new features.
  * These will be removed in a subsequent update, eventually.
* Added color options to tank sizes that were "missing", now that the options no longer spams the menus.
* New additional color choices:
  * size 0: White/Black
  * Size 1: Black
  * Size 2: Black, White/Black
  * Size 3: Black, White/Black, Orange
* Fuel switching turned on by default.
  * Will still use Interstellar Fuel Switch if available, otherwise defaults to FSfuelSwitch.
  * Radial canister tanks switch fuels with color selection.
  * Small "probe" tanks now have choices between LFO, Xenon, or Monopropellant.
  * "Nuclear" tanks now have LF, Oxidizer, Monopropellant, and Xenon options, but remain single-propellant tanks.
* Various minor mesh/texture fixes.
* Restored flag and agency icons to PNG format instead of DDS.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #47 - 1.0 (2015-07-17) - Major Overhaul
* updates #26 - Previous Releases

---

## 0.11.2.0 (2015-07-06) - Minor update

* Corrected a mistake in Modular Fuel Tanks config for the cube tanks.
* Added an optional "FuelTanksPlus_RemoveShrouds" ModuleManager config. To disable auto-shrouds, change from "txt" to "cfg".
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #46 - 0.11.2 (2015-07-06) - Minor update
* updates #26 - Previous Releases

---

## 0.11.1.0 (2015-06-14) - `One more tank!`

* Added white 3.75m 2x tank.
* Added missing MFT/IFS configs for the 3.75m nuke tank.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #45 - 0.11.1 (2015-06-14) - One more tank
* updates #26 - Previous Releases

---

## 0.11.0.0 (2015-06-12) - New things

* Added support for Modular Fuel Systems (Modular Fuel Tanks).
* Added support for Deadly Reentry.
* Added white and orange double-length 2.5m tanks.
* Added 3.75m nuclear (LF-only) tank (one length for now).
* Reconverted textures to DDS format (again).
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #44 - 0.11 (2015-06-12) - New things
* updates #26 - Previous Releases

---

## 0.10.1.0 (2015-05-28) - Appearance tweaks

* Altered sheen/specular on nuclear LF tanks, and size 3 "silver" tanks.
* corrected a mesh mistake on the 2.5m nuclear tanks.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #43 - 0.10.1 (2015-05-28) - Appearance tweaks
* updates #26 - Previous Releases

---

## 0.10.0.0 (2015-05-22) - More tanks

* Added a pair of 1.25m nose cone fuel tanks
* Added 3 tiers of single-propellant radial tanks (LF, Oxidizer, or MonoProp
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com
* closes #42 - 0.10 (2015-05-22) - More tanks
* updates #26 - Previous Releases

---

## 0.9.1.0 (2015-05-19) - Hot fix

* Fixed Interstellar Fuel Switch config for S3-10800 tank.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com>
* closes #41 - 0.9.1 (2015-05-19) - Hot fix
* updates #26 - Previous Releases

---

## 0.9.0.0 (2015-05-19) - Balance tweaks, Nuclear tanks

* Re-balanced the Oscar-like tanks to correspond to the Oscar-B changes.
* Adjusted Interstellar Fuel Switch config to not load if CryoEngines is installed (so Cryo can do the right thing).
* Added LF-only tanks (1.25m and 2.5m) for use with nuclear engines.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com>
* closes #40 - 0.9 (2015-05-19) - Balance tweaks, Nuclear tanks
* updates #26 - Previous Releases

---

## 0.8.2.0 (2015-05-08) - Fixes, 1.0.2 tweaks

* Tweaked attachment node priority order on many tanks for easier attachment in the VAB.
* Changed the "fuel switching" configs to support Interstellar Fuel Switch.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com>
* closes #39 - 0.8.2 (2015-05-08) - Fixes, 1.0.2 tweaks
* updates #26 - Previous Releases

---

## 0.8.1.0 (2015-05-01) - Fixes, 1.0.1 tweaks

* Corrected the S3-2400 Titan nose tank to be in Large Volume Containment tech node.
* Converted textures to DDS format.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com>
* closes #38 - 0.8.1 (2015-05-01) - Fixes, 1.0.1 tweaks
* updates #26 - Previous Releases

---

## 0.8.0.0-beta (2015-04-28) - Beta + KSP 1.0 updates

* Corrected Xenon options for Fuel Switcher.
* KSP 1.0 fixes, including but not limited to:
  * Costs, max temps, and tech tree assignments of all fuel tanks
  * Mass adjustments on 0.625m and 3.75m tanks
  * Capacity adjustments on tanks close to Oscar-B
  * Fixed bottom attachment nodes
  * Added attachment profile settings
  * Increased scale of "triangular" tanks by 25% to make them align nicely with the small cubes.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com>
* closes #37 - 0.8 (2015-04-28) - Beta + KSP 1.0 updates
* updates #26 - Previous Releases

---

## 0.7.1.0-beta (2015-03-25) - Beta

* Corrected fuel capacity of the FL-T50 fuel tank.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com>
* closes #36 - 0.7.1 (2015-03-25) - Beta
* updates #26 - Previous Releases

---

## 0.7.0.0-beta (2015-03-19) - Beta

* Moved the 3.75m nose cone tanks to the "Very Heavy Rocketry" tech node (alongside the other 3.75m tanks)
* Corrected the attachment node size for the 3.75m nose cone tanks.
* Added "bottom" dome parts for external tanks, in both 2.5m and 3.75m.
* Added FL-T50 fuel tank.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com>
* closes #35 - 0.7 (2015-03-19) - Beta
* updates #26 - Previous Releases

---

## 0.6.0.0-beta (2015-03-02) - Beta, tweaks

* Adjusted normals (light/shadow angles) on many of the fuel tanks.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com>
* closes #34 - 0.6 (2015-03-02) - Beta, tweaks
* updates #26 - Previous Releases

---

## 0.5.0.0-beta (2015-02-18) - Beta, probes

* Added several probe/satellite tanks:
  * Three LFO "cube" tanks in varying sizes.
  * Two "triangular" tanks, one with LFO and the other with Xenon.
* Added support for Fuel Switcher.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com>
* closes #33 - 0.5 (2015-02-18) - Beta, probes
* updates #26 - Previous Releases

---

## 0.4.0.0-beta (2015-02-07) - Beta

* Fixed the cap-shrouds to be hidden from the menu icons for the 1.25m tanks.
* Changed TweakScale config to use wildcards instead of duplicating settings for every tank.
* Altered appearance of the grey "Oscar" 0.62m tank to have fewer ribs.
* Renamed most tanks to have better name sorting alongside the stock tanks.
* Mildly increased torque/breaking strength on 1.25m, 2.5m, and 3.75m cylindrical tanks.
* Added three more 0.625m "Oscar" tanks in several sizes, with a spread of mass/fuel/size ratios to fill the gaps.
* Added Orange/White 2.5m and 3.75m tanks that are 3/4 the length of the longest stock tanks in those sizes.
* Added white 2.5m and 3.75m tanks that are half the length of the smallest stock tanks in those sizes.
* Co-Authored-By: NecroBones <10134364+NecroBones@users.noreply.github.com>
* closes #32 - 0.4 (2015-02-07) - Beta
* updates #26 - Previous Releases

---

## 0.3.0.0-beta (2015-02-02) - Beta, more tanks

* Added three 0.625m tanks.
* closes #31 - 0.3 (2015-02-02) - Beta, more tanks
* updates #26 - Previous Releases

---

## 0.2.1.0 (2015-01-28) - Beta fixes

* Removed excess oxidizer from fueled nose cones.
* closes #30 - 0.2.1 (2015-01-28) - Beta fixes
* updates #26 - Previous Releases

---

## 0.0.2.0 (2015-01-28) - `More tanks!`

* Added three 1.25m tanks.
* closes #29 - 0.2 (2015-01-28) - More tanks
* updates #26 - Previous Releases

---

## 0.0.1.0 (2015-01-23) - Initial Beta

* First release.
* closes #28 - 0.0.1.0 (2015-01-23) - Initial Beta
* updates #26 - Previous Releases

---
