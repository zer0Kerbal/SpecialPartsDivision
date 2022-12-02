---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.1
Special Parts Division (SPD)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# Special Parts Division (SPD)

[Home](./index.md)

Special parts... _just special_... Klockheed Martian Special Parts Division, a parts addon for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `KlockheedMartian` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/KlockheedMartian/SpecialPartsDivision`
* Extract the package's `KlockheedMartian` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/KlockheedMartian` --> `<KSP_ROOT>/GameData/`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/KlockheedMartian/SpecialPartsDivision`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/KlockheedMartian/SpecialPartsDivision`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/KlockheedMartian/SpecialPartsDivision`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [KlockheedMartian]
      + [SpecialPartsDivision]
        + [Compatibility]
          ...
        + [Contracts]
          ...
        + [Flags]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        * #.#.#.#.htm
        * Attributions.htm
        * CC-BY-ND-4.0.txt
        * changelog.md
        * ManualInstallation.htm
        * readme.htm
        * SpecialPartsDivision.version
    ...
    * [Module Manager][mm] or [Module Manager /L][mml]
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [Klockheed Martian Ltd (KML)][KML]

[KML]: https://forum.kerbalspaceprogram.com/index.php?/topic/207651-* "Klockheed Martian Ltd (KML)"
