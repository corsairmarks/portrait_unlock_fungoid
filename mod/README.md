# Overview

Do you love fungoids?  Do you wish the large "mushroom" portrait came in more colors?  You're in luck!  The game has 8 colors plus two different spore colors available, but restricts players to only using 4 colors (with different spore colors - for a total of 8 portraits).  This mod allows you to have more colorful mushrooms for a truly psychedelic experience.

# Changes

Enables all variants of the `fun11` portraits, now divided into two phenotypes.  The first phenotype has blue spores, the second phenotype has green spores.  The colors are in this order: red, pink, purple, blue, orange, yellow, green, turquoise.  As a bonus: the game had predefined particle effects for blue and green spores.  Previously all portraits were using the blue spore particle effects, and now each phenotype uses the appropriately-colored particle effects.

Also, there was one color of `fun08` that was omitted, so that is enabled as well.  All other built-in fungoid portraits already allow for every variant to be selected.

## Compatibility

Everything that doesn't change these same portraits.

As a graphics-only mod, yes this is **achievement compatible**.

### When to Install

You can add this to your savegame at any time, although you will experience some leaders with the `fun11` portrait group change colors.  This is due to the portraits now being split across multiple phenotypes.  It should be safe to remove at any time, but I'm unsure what would happen to any leaders that were using the second phenotype.  Back up your savegame before trying to remove a mod, even this one.

## Changelog

* 1.0.0 Initial version

## Source Code

Hosted on [GitHub](https://github.com/corsairmarks/portrait_unlock_fungoid)

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.