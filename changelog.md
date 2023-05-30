# Changelog  
  
| modName    | Special Parts Division (SPD) by dtobi                             |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-ND-4.0+ARR                                                  |
| author     | dtobi and zer0Kerbal                                              |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/208046-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/SpecialPartsDivision)   |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/SpecialPartsDivision) |
| spacedock  | (https://spacedock.info/mod/3024)                                 |
| ckan       | SpecialPartsDivision                                              |

## Version 2.2.99.0-adoption - `<Thank you dtobi>` edition

* Released
  * 30 May 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

* 📌 Pinned
  * Dependencies:
    * [Klockheed Martian Ltd (KML)](https://www.curseforge.com/kerbal/ksp-mods/KlockheedMartianLtd)

## Change Summary 2.2.99.0

### Adoption by [zer0Kerbal](https://github.com/zer0Kerbal)

### Tags

* Add Missing Tags
* all parts missing tags
* add generic `tags = klockheed martian special parts division spd`
  * will need to update to fill in part specific data
* closes #36 - Add Missing Tags

### Update Model Path

* change model = path
  * was: model = Klockheed_Martian_Special
  * now: model = KlockheedMartian/SpecialPartsDivision
  * now parts show up in game
* closes #38 - Update Model Path

### Asset Updates

* create Assets/ folder
* convert from mesh to MODEL
* convert
  * from tga to png
  * was: tga (8.4 mb)
  * now: png (1.8 mb)
* rename
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* relocate part.cfg to Parts/
* closes #35 - Asset Updates

### Part Localization

* create agency
* run localizer
* Parts to localize
  * [fairing-grey.cfg]
  * [fairing-1-1.cfg]
  * [fairing-1.cfg]
  * [endpoint-1.cfg]
  * [decoupler-3-long.cfg]
  * [decoupler-1-long.cfg]
  * [decoupler-1.cfg]
  * [decoupler-3.cfg]
  * [crocodile-2.cfg]
  * [crocodile-1.cfg]
  * [parttank.cfg]
  * [refurbish.cfg]
  * [partbox.cfg]
  * [part.cfg]
  * [skylab.cfg]
  * [hatch.cfg]
  * [lens.cfg]
  * [engine-mount1.cfg]
  * [part.cfg]
  * [inflatable.cfg]
  * [infla.cfg]
  * [infla.cfg]
  * [door.cfg]
  * [window.cfg]
  * [bay-1-short.cfg]
  * [bay-1.cfg]
* create Localization/
  * create <en-us.cfg>
  * create [readme.md] v2.1.1.0
  * create [quickstart.md] v1.0.1.0
* updates #6 - Localization - Master
* closes #7 - American English <us-en.cfg>
* closes #23 - Part Localization

### Recreate Prior Releases

* Releases
* closes #24 - Releases to be archived
* closes #25 - 2.0.0.0-release
* closes #26 - 2.0.1.0-release
* closes #27 - 2.1.1.0-release
* closes #28 - 2.1.2.0-release
* closes #29 - 2.1.0.0-release

### Status

* Issues
  * closes #2 - Special Parts Division 2.2.99.0-adoption <NAME>
  * closes #3 - 2.2.99.0 Verify Legal Mumbo Jumbo
  * closes #4 - 2.2.99.0 Create Documentation
  * closes #5 - 2.2.99.0 Create Social Media

## Version 2.2.0.0-release

* raidernick
* missing archive

* Fixed part animations
* Fixed part scaling, remove mm config fix if you have it
* Converted all textures to MBM to fix tga issues
* Removed broken tweak scale version from zip, please download latest version here(YOU NEED IT): http://forum.kerbalspaceprogram.com/threads/80234
* Updated info for new license

### Using the wet workshop parts

* You can turn any fuel tank (even 5m KW Rocketry Tanks) into a space station now. Follow these steps:
  * Attach the door to a tank
  * Launch your rocket and drain the tank COMPLETELY. (Smart Parts has a fuel valve to help with that!)
  * Bring supplies and transfer these to the door.
  * Klick the door and convert empty tanks to empty space to living space
  * Bring kerbals to the door
* Right now all happens in the door. Depending on the feedback, I might continue this and extend it with connected living space support, etc

---

## Version 2.1.2.0-release

* closes #24 - Releases to be archived
* closes #28 - 2.1.2.0-release
* missing release notes

---

## Version 2.1.1.0-release

* updates #24 - Releases to be archived
* closes #27 - 2.1.1.0-release
* missing release notes

---

## Version 2.1.0.0-release

* Wet workshop parts
* Hopefully a fix for the COM bug with the windows
* closes #29 - 2.1.0.0-release
* updates #24 - Releases to be archived

---

## Version 2.0.1.0-release

### New Klockheed Martian Structure and Tubes and Hatches

* More stability and wet workshops
* New Tweakscale
* Less tight integration with km_lib.dll
* Wet workshop parts

* updates #24 - Releases to be archived
* closes #26 - 2.0.1.0-release

---

## Version 2.0.0.0-release

### Skylab IVA and new folder structure

* Skylab Iva
* New folder structure
* Space telescope parts
* New black tubes for Hubble-like telescopes
* Hatch for Hubble-like telescopes
* Please delete ALL old Klockheed Martian folders before installing the V2.0 Thank you!
* Lens for telescopes
* updates #24 - Releases to be archived
* closes #25 - 2.0.0.0-release

## Version 0.3.0.0-release

### More resizable parts and Skylab

* New Skylab science laboratory
* More resizable parts: Crocodiles (Thanks Floppster)
* Half size cargo bay (Thanks Floppster)
* Corrected the size of the large shrouds
* missing release archive

## Version 0.2.0.0-release

### Tweakscale integration an mesh fixes

* Added Tweakscale to reduce part count (Thanks Floppster)
* Corrected collision meshes for cargo bay and long shroud
* missing release archive

---

## Version 0.1.0.0-release

* Initial release by dtobi
* missing release archive

---
<!-- THIS FILE: CC BY-ND 4.0 by zer0Kerbal -->