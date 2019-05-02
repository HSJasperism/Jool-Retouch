# Jool-Retouch

Forum link:
https://forum.kerbalspaceprogram.com/index.php?/topic/183257-wip-16x-jool-retouch/

 Goal: bring stock Jool up to par with the quality of the base OPM gas giants, while maintaining mostly stock colors. Inspired by Snark's JoolBiomes

Mostly a proof-of-concept of https://www.seedofandromeda.com/blogs/49-procedural-gas-giant-rendering-with-gpu-noise

Subgoals:

    1024x512 scaled space texture (same size as base OPM)
    Indexed, colored biome map, with Kerbnet colors
    (incomplete) Biome maps for supported visual mods (SciFi is currently possible)
    (incomplete) Science flavor text for the different biomes
    (incomplete) Jupiter-esque dust ring
    (incomplete) EVE-based storms and cloud swirls (optional)

Required: Module Manager, Kopernicus

Recommended: OPM, EVE, Realistic Atmospheres, Custom Asteroids + OPM configs

Incompatible: Most visual overhaul mods that affect Jool

The mod disables itself when unsupported visual overhaul mods are detected. Most of the popular visual overhaul mods change Jool enough so that the biome map added by this mod is pointless (and the updated scaled space/EVE clouds they provide are much better than the ones this mod gives). Custom biome maps will be included for supported mods. 
