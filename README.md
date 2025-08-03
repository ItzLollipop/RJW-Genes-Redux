# RJW-Genes-Redux [NSFW]

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This fork has a goal purpose of restructuring Genes and Gene Inheritance. Removal of sphaghettified .XML lines of code and seperation of patches outside of main code for a clean build and universal support and syntax between Race Support Redux and RJW Core.

## Race Support Redux

* https://github.com/ItzLollipop/RJW-Race-Support-Redux/tree/main

## Current Features 

* Supports Race Support
    * Added genetical inheritance for simple genital types for now.
    * Groundwork for modularization of genetical inheritance by RaceGroups.
## Planned Features

* Early game ability to "use" biotech by breeding Pawns, giving players more incentive to grow their colony versus other mechanics like imprisonment recruitment, quests or ideological events.
    * Balance for genes; All pawns will have gene tags that have a chance to trigger during biotech pregnancy. They can be good or bad, maybe neither and they're just cosmetic. Certain pawns may have rare or extremely rare percentage rolls for rare genetical traits that you may want.
* Script or WebUI equivalent for creation of additional add-on packages from modded races whether they're humanlike pawns or animal pawns.
    * Quick creation of files for users or mod creators to patch their races.

## Compatibility Patches 

None Necessary.

## Structure

- Toplevel: By Function (i.E. "Genes", "Animal Inheritance", "Utility")
- Then: By Domain, following the Gene-Categories ("Cosmetic","Special", "Damage",...)
- Last: By Type of Action (Def, Patch, etc.)
