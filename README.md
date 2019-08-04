# glowise (no longer maintained)
Glowing ores for Starbound's ISE-3 mod

Introduction
------------

Starbound's [Industrialization 3: Starbound Edition (ISE-3)](http://community.playstarbound.com/index.php?resources/industrilization-3-starbound-edition-ise-3.2531/) mod by DraLUSAD _et al_ adds many functionalities into the game.
With one of those things come new ore (Tin) and various gemstones as mine-able tiles.

However, these tiles are unfortunately not affected by ore illumination mods, such as [Illuminated Ores](http://community.playstarbound.com/index.php?resources/illuminated-ores.2429/) by Amadox. This is because the ore illumination is done by JSON-patching the tiles files individually so that they emit radiant light. Doing so does not extend to modded ores and therefore ISE-3 ores do not glow.

Features
--------

This mod, glowise, illuminates the ores introduced by ISE-3. That's it.

Requirements
------------

You need ISE-3 to run this mod. You may want to get Illuminated Ores as well, because this mod does not illuminate vanilla ores, something Amadox (above) has already mastered.

Installation
------------

You can download glowise from the releases page (https://github.com/LunaticNeko/glowise/releases) or clone it using Git.

To clone with Git, go to your starbound/giraffe_storage/mods directory (or any directory that stores mods in your version), and then git clone this repository.

If you downloaded it as a ZIP, extract it in a way that you have a directory structure that has /starbound/giraffe_storage/mods/glowise/glowise.modinfo. It has to look like that or it won't work. I don't know how Github manages releases but I'll get around to do a .zip and .modpak releases whenever possible.

The ores should glow even on already-visited planets, as the patches target ore tiles and not world generation.

To uninstall, remove the starbound/giraffe_storage/mods/glowise directory or the modpak. There should be no error caused by uninstallation unless other mods depend on glowise and you break their requirements.

Issues
------

* Please recommend me with changes in parameters of each ISE-3 ore's glow. My taste in color (and my monitor) is not very good, so I'm working with what I feel good enough. If possible, please use Github's issues features or send a pull request.
* This mod is strategically named to exploit Starbound's reverse-alphabetic (or "descending", you terminology geeks) mod load ordering because the modinfo dependency system is not functioning properly. I have added an include clause to the modinfo file (Thanks Dr_Capsaicin on Reddit) and it should mitigate the problem, but if you encounter anything please tell me. If something goes wrong in this case, the game won't crash but the ore won't glow.

Received Suggestions & Future Work
----------------------------------

* Suggestion: Support Frackin Universe. I don't know if it's easy and efficient to just mash all the patches in a single mod, but if that can be done then it would be done. Otherwise, I will create a new mod, and a mod-pack that combines everything.

Compatibility
-------------

I develop this mod on nightly. It should work all the way down to stable. I tested this mod on an existing character and an existing planet, and it works fine. If it doesn't, please tell me.

Threats to compatibility include ISE-3 (theoretically anything this mod depends on) adding/removing/changing ore tiles files, and Starbound changing their mod load order structure. I will do my best to keep glowise compatible with latest ISE-3 on Starbound nightly.

No longer maintained since last commit. I will not comment on FU compatibility as I do not personally play that modpack.

Licensing
---------

Thanks to DraLUSAD, ISE-3's author, for the confirmation of permission to *PATCH* the mod. *NO ENDORSEMENT OR AFFILIATION IS IMPLIED*.

For my contribution or work in this mod, please treat this mod like other Starbound mods that have following as their copyright notice:

* Mod Pack Permissions: Anyone can use this mod in their mod compilation without the author's consent.
* Mod Assets Permissions: Anyone can alter/redistribute the mod's assets without the author's consent.

However, *attribution is required*.
