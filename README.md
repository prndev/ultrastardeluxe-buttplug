buttplug.io client for UltraStar Deluxe Karaoke Game

„Plug-in and Sing“

![UltraStar Deluxe Buttplug Logo](https://github.com/prndev/ultrastardeluxe-buttplug/blob/main/ultrastardx-buttplug-icon.svg)

The toy's intensity increases with the player's rating (as indicated with the small bar below the points).

Needs UltraDtar Deluxe v2024.8.0 or newer.  
Tested on Ubuntu 22.04 – experience on Windows may vary.
Tested with one toy only (I only have one).

Depencencies:

* „ultrastardx“ built against lua5.2 or newer
* „Intiface Central“ v2.5.5 (newer versions may work) from https://intiface.com/central/
* „pollnet“ binary v1.1.0 (newer versions may work, use lib32 variant on Windows) from https://github.com/probable-basilisk/pollnet/releases/tag/v1.1.0
* „cffi“ 0.2.3 installed via `sudo luarocks-5.2 install cffi-lua` (newer versions may work)

On Ubuntu 24.04, `luarocks-5.2` needs `sudo apt install lua5.2 meson` to build `cffi-lua` against `lua5.2`.
A different ffi module may work. However, changes may be necessary in pollnet.lua.

This repostory includes:

* „pollnet“ bindings v1.1.0 (newer versions may work, use lib32 variant on Windows) from https://github.com/probable-basilisk/pollnet/releases/tag/v1.1.0
* „buttplug-lua“ 9697af1 (modified) originally from https://github.com/abbihors/buttplug-lua

### Installation

Merge the plugins folder.

Optionally, add lines to `languages/English.ini` (or whatever language you are using):
 
    MODE_BUTTPLUG_NAME=Buttplug
    MODE_BUTTPLUG_DESC=Toy intensity increases with your rating!
