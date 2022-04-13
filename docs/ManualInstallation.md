---
permalink: /ManualInstallation.html
title: ManualInstallation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
# layout: bare
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.5.0
Fuel Tanks Plus (FTP)
created: 01 Oct 2019
updated: 11 Apr 2022 -->

<!-- based upon work by Lisias -->

# Fuel Tanks Plus (FTP)

[Home](./index.md)

A set of fuel tanks that are 1.5x the length of the largest stock tanks in each diameter, plus fuel-filled nose cones for those diameters. These tanks are meant to give you some visual choice of styles that are loosely inspired by real-world rockets from NASA, ESA, and private space firms (though that inspiration is mainly in color choice), while maintaining the style established in the Color Coded Canisters mod (since CCC replaces stock visuals, any 'new' tanks should be spun off into a separate pack, and hence we have FTP) For Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the NecroBones folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/NecroBones/FuelTanksPlus`
* Extract the package's `NecroBones/` folder into your KSP's GameData as follows:
  * `<PACKAGE>/NecroBones` --> `<KSP_ROOT>/GameData/NecroBones`
    * Overwrite any preexisting file.

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/NecroBones/FuelTanksPlus`
* Extract the package's `GameData/NecroBones/` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData/` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [NecroBones]
      + [FuelTanksPlus]
        + [Agencies]
          ...
        + [Assets]
          ...
        + [Compatibility]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        * #.#.#.#.htm
        * changelog.md
        * License.txt
        * readme.htm
        * FuelTanksPlus.version
    ...
  * KSP.log
  ...
```

### Dependencies

* none
