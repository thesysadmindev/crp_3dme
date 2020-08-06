# 3D /me
The /me command but it's 3D printed.

<img src=https://imgur.com/lJZbcGA.png>

## Installation
* Download the resource ;
* Drag and drop it into your resources folder ;
* Add ```ensure 3dme``` to your server configuration file.

## How to use
* In the chat, type /me followed by your action.

## Options 
* Color of the text : ```client.lua``` line 14 : ```local color = { r = 230, g = 230, b = 230, a = 255 }```
* Font of the text : ```client.lua``` line 15 : ```local font = 0``` Available fonts : https://imgur.com/a/oV3ciWs
* Time on screen : ```client.lua``` line 4 : ```local displayTime = 5000```

## Updates

To see the previous changelogs, please refer to the [FiveM forum post](https://forum.cfx.re/t/release-me-but-the-text-is-3d-printed/).

#### V2.1
* Added Onesync Infinity support thanks to *@glitchdetector* ;
* Replaced `__resource.lua` by its new version `fxmanifest.lua`.

## Note
* This may not work if are you using a custom chat resource.
* This could conflict with other /me scripts (disable them).
