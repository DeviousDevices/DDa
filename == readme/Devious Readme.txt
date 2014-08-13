DEVIOUS DEVICES: ASSETS (v2.8.2)
for TES V: Skyrim
by Zadil



CONTENTS:

Description
Usage
Requirements
Known Issues
FAQ
Credits
Version History



DESCRIPTION

This is a collection of BDSM-themed gear and devices for the CBBE 3.2.3 (Curvy) & UNPB 2.5.2 female body, with additional tweaks for the UNP 1.2 (Skinny) body included.

It is strongly recommended to use this package in conjunction with the 'Devious Devices: Integration' mod by Min.

A list of mods that use these devices can be found here:
http://www.loverslab.com/topic/30855-devious-skyrim/#entry770752



USAGE (for Users)

Simply drop the contents into your Skyrim Data folder.

Use these files together with other Devious Devices mods to access the content ingame.



USAGE (for Modders)

You are free to reference the contents of the esm in any way you see fit within the context of your own Skyrim mod, but please do not merge its contents with your own mod or repack/redistribute any part of it without expressed permission. These assets are provided for the purpose of Skyrim modding only.

This mod adds several new entries under the 'Armor', 'ArmorAddon' and 'Keywords' categories inside of the CK.
All new additions start with a 'zad_' prefix (example: zad_plugPrimitive) so they should be easy to filter.

Items that end with '_scriptInstance' are included as instances for external scripts only (i.e. player interaction) and should -not- be used without a specific reason as they will not appear in the player inventory. Use the other item IDs instead.

The '\textures\devious\books' directory contains several drawing-like images that can be used as book graphics for in-game documents like books and notes.

Please refrain from referencing any of the following items in your mod(s) as they have become obsolete and may be excluded from future releases:
- padded Cuffs (complete) [made redundant by the individual cuff parts]
- all plug pair items (the ones who don't end with 'An' or 'Vag') [made redundant by individual plugs]

The equipment pieces use the following body slot configuration:

Armbinder: 33, 59
Blindfold: 55
Body Harness: 45, 49
Chastity Belts: 49
Chastity Bra: 56
Collars: 45
Cuffs (Arms): 59
Cuffs (Legs): 53
Cuffs (Neck): 45
Gag Mouthpieces: 44
Gag Straps: 50
Nipple Piercings: 56
Plugs (Anal): 48
Plugs (Vaginal): 54
Vaginal Piercings: 48



REQUIREMENTS

CBBE v3.2.3 (Curvy) / UNPB 2.5.2 / UNP 1.2 (Skinny)
The assets were created for the CBBE 3.2.3 (curvy) and UNPB 2.5.2 female body. A slightly tweaked version for the UNP 1.2 (skinny) body is also included.
Other body types and variations are not officially supported and may result in visual anomalies.

SexLab Framework
Some items in this package have SexLab keywords attached to them to ensure compatibility with other adult mods.



KNOWN ISSUES

Headgear (gags, blingfold,...) may not always fit perfectly depending on the character's race and facial features.

Minor clipping and/or deformation issues may occur when the character assumes extreme poses or performs certain movements.



FREQUENTLY ASKED QUESTIONS

Q: How do I access or use these devices? 
A: 'Devious Devices: Assets' is a modder's resource and doesn't place the items ingame nor assign them or provide support for custom ingame behaviour - these aspects are handled and maintained by seperate 'Devious Devices' mods. Any issues with such should thus be referred to the respective mod author.

Q: Why do the piercings appear misaligned?
A: The piercings only support certain bodytypes as chosen during the installation. They won't appear correctly on other bodies.

Q: Can I use these items in my own mod?
A: Yes, just make sure to take a look at the 'Usage' section above.

Q: Will there ever be support for males or beast races?
A: Unlikely due to lack of public and personal interest.

Q: Can I make suggestions regarding future content?
A: Ideas about additional devices can be shared in the 'Devious Devices: Assets' support thread, though no promises are made that suggestions will be realized, particularly those that would require custom animations.

Q: When will the next version of 'Devious Devices: Assets' be released and what will be included?
A: No idea



CREDITS

Min
for his outstanding and ongoing work on the Integration mod

Ashal
for providing and maintaining the SexLab framework

Chris
for his work on the Zaz Animation pack

Coopervane
for his input & contributions regarding nif shader parameters

All DD modders and beta testers
for their time and efforts



VERSION HISTORY

2.8.2
- Added: nipple piercings (soulgem)
- Added: vaginal piercings (soulgem)

2.8.1
- Other: Removed optional 1st person fix

2.8.0
- Added: posture collar (leather)
- Tweak: enhanced padded cuffs texture
- Other: BAIN & FOMOD installer support

v2.7.5
- Added: several new 2d book graphics
- Tweak: overhauled shader parameters
- Fixed: inconsistent mesh normals
- Fixed: reversed padded collar uvs
- Other: UNPB support resumed

v2.7.0
- Added: body harness
- Added: leather cuffs
- Added: blindfold
- Added: panel gag (open) version
- Added: panel gag plug (misc object)
- Added: gag variations without harness straps
- Added: padded chastity belt without backplate
- Added: separate vaginal & anal versions of existing plugs
- Tweak: armbinder split into separate sleeve and collar items
- Tweak: added buckle & padlock to leather collar mesh
- Tweak: revised overall item reflectivity
- Tweak: some plugs & posture collar texture adjustments
- Tweak: devices now wearable by Skeletons, Elders & Manakins
- Tweak: weight/value/text adjustments to several devices
- Tweak: misc adjustments to world object nif parameters
- Tweak: device name changes for better inventory organization
- Tweak: several changes to file structure and CK armor setup
- Tweak: cleared devices of unnecessary keywords
- Fixed: metal stud placement on armbinder mesh
- Fixed: some faulty normal map textures
- Other: UNPB support officially discontinued 

v2.6.2
- Added: 3 harness gags
- Added: new keywords
- Tweak: fixed compatibility between cuffs and armbinder

v2.6.0
- Added: armbinder
- Added: a few new keywords
- Tweak: items names (IDs left untouched)
- Tweak: inventory appearance of items
- Tweak: inflatable plug glossiness
- Fixed: normal tangents of nif files
- Fixed: world models not displaying properly inside the CK

v2.5.0
- Added: several texture variants of the soulgem plug
- Added: 'zad_HasPlugs' keyword
- Other: introduced Sexlab dependency

v2.0.1
- Fixed: dirty keyword reference

v2.0.0
- Added: chastity bra, cuffs, posture collar, soulgem plugs
- Tweak: overhauled textures and several mesh edits
- Tweak: objects assigned different object IDs
- Tweak: plugs are now interchangeable between belts
- Fixed: belt clipping issue around belly area (CBBE)
- Other: made into an esm resource pack

v1.2.0
- Added: new belt with custom plugs
- Fixed: weight interpolation error affecting cbbe version

v1.1.0
- Tweak: chastity belts are now craftable and interactive
- Tweak: attachments are now separate objects
- Tweak: changed location of contents (Arcanaeum)
- Other: mod now requires the Zaz Animation Pack

v1.0.1
- Tweak: belts now occupy body slot 49 instead of 52

v1.0.0
- Initial release