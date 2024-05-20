buttplug.io client for UltraStar Deluxe Karaoke Game

„Plug-in and Sing“

The toy's intensity increases with the player's rating (as indicated with the small bar below the points).

**For reasons beyond my understanding, the relative imports can only work
when the plugins folder is the working directory.**

Tested on Ubuntu 22.04 – experience on Windows may vary.
Tested with one toy only (I only have one).

Depencencies:

* „ultrastardx“ v2024.5.1 (other versions may work) built against lua5.3 (other versions may work) from https://github.com/UltraStar-Deluxe/USDX/releases/tag/v2024.5.1 
* „Intiface Central“ v2.5.5 (newer versions may work) from https://intiface.com/central
* „pollnet“ binary v0.5.1 (newer versions may work) from https://github.com/probable-basilisk/pollnet/releases/tag/v0.5.1
* „cffi“ 0.2.3 installed via `luarocks-5.3 install cffi-lua` (newer versions may work)

A different ffi module may work. However, changes may be necessary in pollnet.lua.

This repostory includes:

* „pollnet“ bindings v0.5.1 (newer versions may work) originally from https://github.com/probable-basilisk/pollnet/releases/tag/v0.5.1
* „buttplug-lua“ 9697af1 (modified) originally from https://github.com/abbihors/buttplug-lua

### Installation

Merge the plugins folder.

Optionally, add lines to `languages/English.ini` (or whatever language you are using):
 
    MODE_BUTTPLUG_NAME=Buttplug
    MODE_BUTTPLUG_DESC=Toy intensity increases with your rating!
