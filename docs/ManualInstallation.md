---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
# layout: bare
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.1
Fuel Tanks Plus (FTP)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# Fuel Tanks Plus (FTP)

[Home](./index.md)

A set of fuel tanks that are 1.5x the length of the largest stock tanks in each diameter, plus fuel-filled nose cones for those diameters. These tanks are meant to give you some visual choice of styles that are loosely inspired by real-world rockets from NASA, ESA, and private space firms (though that inspiration is mainly in color choice), while maintaining the style established in the Color Coded Canisters mod (since CCC replaces stock visuals, any 'new' tanks should be spun off into a separate pack, and hence we have FTP) For Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the FTP folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/FuelTanksPlus/FuelTanksPlus`
* Extract the package's `FuelTanksPlus` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/FuelTanksPlus` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/FuelTanksPlus/FuelTanksPlus`

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/FuelTanksPlus/FuelTanksPlus`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData/` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/FuelTanksPlus/FuelTanksPlus`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [FuelTanksPlus]
      + [Fuel Tanks Plus Ltd (FTPL)][FTPL]
        ...
      + [FuelTanksPlus]
        + [Compatibility]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        * #.#.#.#.htm
        * Attributions.htm
        * CC-BY-NC-SA-4.0.txt
        * changelog.md
        * FuelTanksPlus.version
        * ManualInstallation.htm
        * readme.htm
        ...
      ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [Fuel Tanks Plus Ltd (FTPL)][FTPL]

[FTPL]: https://forum.kerbalspaceprogram.com/threads/209628-*/ "FTP Ltd"
