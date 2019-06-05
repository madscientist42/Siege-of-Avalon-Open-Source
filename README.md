# Siege of Avalon : Open Source #

_"Siege of Avalon : Open Source is an attempt to keep this great isometric RPG game alive by continuing development on it. Our aim is to create a SDL version of the engine that will work on Win32, Linux and where ever Pascal compilers and SDL are supported."_


This is a composite re-fork from the [**gondur/Siege-of-Avalon-Open-Source**](https://github.com/gondur/Siege-of-Avalon-Open-Source) and [**SteveNew/Siege-of-Avalon-Open-Source**](https://github.com/SteveNew/Siege-of-Avalon-Open-Source) repositories that were derived from a work forked back off by myself of the original source release core and had minimial clean-ups applied with the intent to make it cross-platform.

The main focuses of this fork: 

1. Moving the Win32 source to newer Delphi 10.3 or later including its free Community Editons. **DONE by SteveNew**
2. Moving the source code over to something that is more cross-platform as needed (If Delphi 10.3 works right on Linux and OSX...)
3. Fixing various glitches and heavy refactoring.
4. Include HD/FullHD support like already done by gondur. **DONE by SteveNew**
5. Replace DX with either SDL2/Vulkan/other to gain crossplatform support - this is this Fork's MAIN priority at this time.

Also check out the gondur and SteveNew fork for changes, and the thread on SOAAmigos (in german), where Raptor/Rucksacksepp (http://soamigos.de/wbb5/forum/index.php?thread/4458-hd-und-fullhd-version-zu-siege-of-avalon-aus-dem-source-code-mit-delphi-4/&postID=91286#post91286) fixed building with Delphi 4 amoung other things.  It is the intent of the fork here to do some of the heavy load-lifting for making it cross-platform (which was the original intent of this fork of the original source...) while contributing back/absorbing the community changes of the other forks accordingly so we can have this gem of a game live again.

To play the game (currently) you will need additional files in the assets folder:
- soundlib.dll
- fmod.dll
- DFX_P5S.DLL
- DFX_P6S.DLL

all found in the original free playable 1. chapter/demo - http://soaos.sourceforge.net/FreePage.htm

You must currently include the newest ddraw.dll from [**DDrawCompat**](https://github.com/narzoul/DDrawCompat) - binary can be downloaded under releases. Specific fixes has been applied until a new version of ddraw.dll is released.

Look in the changelog for status, changes and planned changes.
