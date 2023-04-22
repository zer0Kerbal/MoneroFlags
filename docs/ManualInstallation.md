---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.0.0.0
Monero Flags (QBMF)
created: 19 Apr 2023
updated:

TEMPLATE: ManualInstallation.md v1.1.9.0
created: 01 Feb 2022
updated: 27 Mar 2023

based upon work by Lisias -->

# [Monero Flags (QBMF)][mod]

[Home](./index.md)

Monero agent and flags for use in Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `QuickBASIC` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/QuickBASIC/MoneroFlags`
* Extract the package's `QuickBASIC/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/QuickBASIC` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/QuickBASIC/MoneroFlags`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/QuickBASIC/MoneroFlags`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/QuickBASIC/MoneroFlags`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [QuickBASIC]
      + [MoneroFlags][mod]
      + [Agencies]
        ...
      + [Config]
        ...
      + [Localization]
        ...
      + [Flags]
        ...
      * #.#.#.#.htm
      * Attributions.htm
      * CC-BY-SA-4.0.txt
      * changelog.md
      * ManualInstallation.htm
      * MoneroFlags.version
      * readme.htm
      ...
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* none

[mod]: https://www.curseforge.com/kerbal/ksp-mods/MoneroFlags "Monero Flags (QBMF)"

THIS FILE: CC BY-ND 4.0 by zer0Kerbal