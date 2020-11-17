# DU-Prospector
True-range multilateration implementation in LUA for Dual Universe. 

![Example](https://github.com/d6rks1lv3rz3r0/DU-Prospector/raw/main/ProspectorHUD.png)

The ultimate ore scanner triangulation script. Will help you lock onto a node on your scanner with incredible accuracy after you spend about 10 seconds taking 3 scanner measurements. You will find nodes as if you put them there. Comes with an insanely sleek HUD that makes it super easy to use. 
https://cdn.discordapp.com/attachments/761729209454166016/778028669586636839/Prospector.lua

Installation: Copy the contents of the above file, right click a programming board or remote controller -> Paste Lua Configuration from Clipboard!
Guide: https://cdn.discordapp.com/attachments/761729209454166016/778128660682113024/Guide.png

Exported Variables:
- SafeHUDOff: 1 to activate, 0 to decativate Automatic HUD turn off to avoid lag.

Warning! -  If while having a HUD on, you press TAB or Enter to get the pointer out, and you click ANYWHERE other than the chat window (greyed out areas) it will immediately induce lag. Game-wide bug by NQ.

## References
[1] Trilateration and extension to Global Positioning System navigation, Bertrand T. Fang, Journal of Guidance, Control, and Dynamics 1986 9:6, 715-717
[2] https://en.wikipedia.org/wiki/True-range_multilateration#Three_Cartesian_dimensions,_three_measured_slant_ranges
