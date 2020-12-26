# Balance Breaker DS Wiimmfi Guide
This guide explains how to connect to Wiimmfi, a replacement server for the now-defunct Nintendo WFC, on a Nintendo DS/3DS/2DS family console and on the [melonDS](http://melonds.kuribo64.net) emulator (a Nintendo DS(i) emulator for Windows, macOS and Linux) so you can play Nintendo DS games online once again.

## Nintendo DS
1. Find the Nintendo WFC setup in any Nintendo WFC enabled DS game, or if you're on a 3DS/2DS family console you can access the Nintendo WFC setup via the System Settings app.
1. Setup an Internet connection. Note: This will only work with networks that have WEP security or no security. If you're not sure what security your network has, it's most likely WPA/WPA2 unless your router is ancient. In that case, you can either setup an open [guest network](https://www.hellotech.com/guide/for/how-to-set-up-guest-wifi-network) or an easier way is to setup an open mobile hotspot for your console to connect to. *Most* mobile hotspots should work.
1. Set `Auto-obtain DNS` to `No`.
1. Set `Primary DNS` to `164.132.44.106`.
1. Click `Test Connection`. If you followed the instructions correctly it should say `Connection successful`. Now you can connect to Wiimmfi!

## melonDS
1. Download the latest version of melonDS from [here](http://melonds.kuribo64.net/downloads.php) if you haven't already.
1. You will need to obtain these 3 files in order to use the emulator:

   • DS ARM9 BIOS
   
   • DS ARM7 BIOS
   
   • DS firmware
   
   You can dump these files from real hardware with [this](http://kuribo64.net/get.php?id=TWCJjwloQLCYy3Zh) tool. This guide doesn't state any *alternative* methods to obtain these files.
