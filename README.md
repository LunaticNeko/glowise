# glowise
Glowing ores for Starbound's ISE-3 mod

Introduction
------------

Starbound's [Industrialization 3: Starbound Edition (ISE-3)](http://community.playstarbound.com/index.php?resources/industrilization-3-starbound-edition-ise-3.2531/) mod by DraLUSAD _et al_ adds many functionalities into the game.
With one of those things come new ore (Tin) and various gemstones as mine-able tiles.

However, these tiles are unfortunately not affected by ore illumination mods, such as [Illuminated Ores](http://community.playstarbound.com/index.php?resources/illuminated-ores.2429/) by Amadox.

Features
--------

This mod, glowise, illuminates the ores introduced by ISE-3. That's it.

Requirements
------------

You need ISE-3 to run this mod. You may want to get Illuminated Ores as well, because this mod does not illuminate vanilla ores, something Amadox (above) has already mastered.

Installation
------------

To clone with Git, go to your starbound/giraffe_storage/mods directory (or any directory that stores mods in your version), and then git clone this repository.

If you downloaded it as a ZIP, extract it in a way that you have a directory structure that has /starbound/giraffe_storage/mods/glowise/glowise.modinfo. It has to look like that or it won't work. I don't know how Github manages releases but I'll get around to do a .zip and .modpak releases whenever possible.

The ores should glow even on already-visited planets, as we change the ore tiles directly.

To uninstall, remove the starbound/giraffe_storage/mods/glowise directory or the modpak. There should be no error caused by uninstallation unless other mods depend on glowise and you break their requirements.

Issues
------

* Please recommend me with changes in parameters of each ISE-3 ore's glow. My taste in color (and my monitor) is not very good, so I'm working with what I feel good enough. If possible, please use Github's issues features or send a pull request.
* This mod is strategically named to exploit Starbound's reverse-alphabetic (or "descending", you terminology geeks) mod load ordering because the modinfo dependency system is not functioning properly. I have added an include clause to the modinfo file (Thanks Dr_Capsaicin on Reddit) and it should mitigate the problem, but if you encounter anything please tell me. If something goes wrong in this case, the game won't crash but the ore won't glow.

Compatibility
-------------

I develop this mod on nightly. It should work all the way down to stable. If it doesn't, please tell me.

I tested this mod on an existing character and an existing planet, and it works fine.

Licensing
---------

As stated in the project page, ISE-3's author does not allow mod pack redistribution and asset modification. However, since this term does not discuss about *patching* the mod, I am currently in the process of permission request. That means, if it is denied, I will have to delete this repository. I hope nobody hasn't really downloaded this yet. *NO ENDORSEMENT OR AFFILIATION IS IMPLIED*

For my work in this mod, please treat this mod like other Starbound mods that have following as their copyright notice:

* Mod Pack Permissions: Anyone can use this mod in their mod compilation without the author's consent.
* Mod Assets Permissions: Anyone can alter/redistribute the mod's assets without the author's consent.

However, *attribution is required*.
