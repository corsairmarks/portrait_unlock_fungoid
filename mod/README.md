# Overview

Do you love fungoids?  Do you wish the large "mushroom" portrait came in more colors?  You're in luck!  The game has 8 colors plus two different spore colors available, but restricts players to only using 4 colors (with different spore colors - for a total of 8 portraits).  This mod allows you to have more colorful mushrooms for a truly psychedelic experience.

# Changes

Enables all variants of the `fun11` portraits, now divided into two phenotypes.  The first phenotype has blue spores, the second phenotype has green spores.  The colors are in this order: red, pink, purple, blue, orange, yellow, green, turquoise.  As a bonus: the game had predefined particle effects for blue and green spores.  Previously all portraits were using the blue spore particle effects, and now each phenotype uses the appropriately-colored particle effects.

Also, there was one color of `fun08` that was omitted, so that is enabled as well.  All other built-in fungoid portraits already allow for every variant to be selected.

## Compatibility

Everything that doesn't change these same portraits.

Marked as compatible with Stellaris version 3.7 "Canis Minor" but backwards compatible with version 3.5 "Fornax."  As a graphics-only mod, yes this is **achievement compatible**.

### When to Install

You can add this to your savegame at any time, although you will experience some leaders with the `fun11` portrait group change colors.  This is due to the portraits now being split across multiple phenotypes.  It should be safe to remove at any time, but I'm unsure what would happen to any leaders that were using the second phenotype.  Back up your savegame before trying to remove a mod, even this one.

### Recommended Companion Mods

Like graphic fixes for the base game?  Try my mod that enables planetary skies showing the parent planets for habitable moons: [Yet Another Planetary Sky Fix](https://steamcommunity.com/sharedfiles/filedetails/?id=2527918521) (not achievement compatible, however).

## Changelog

* 1.0.0 Initial version
* 1.0.1 Renamed to "Restored Content: Fungoids" and thumbnail updated
* 1.1.0 Flagged as compatible with Stellaris 3.1 "Lem" - no actual changes
* 1.2.0 Flagged as compatible with Stellaris 3.2 "Herbert" - no actual changes
* 1.3.0 Flagged as compatible with Stellaris 3.3 "Libra" - no actual changes
* 1.4.0 Flagged as compatible with Stellaris 3.4 "Cepheus" - no actual changes
* 2.0.0 Update for Stellaris version 3.6 "Orion" (and changes from version 3.5 "Fornax") - `hair` to `attachment`
* 2.1.0 Flagged as compatible with Stellaris 3.7 "Canis Minor" - no actual changes

## Source Code

Hosted on [GitHub](https://github.com/corsairmarks/portrait_unlock_fungoid)

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.