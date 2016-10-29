V.02 INCOMPLETE!

This is the first release, I have attempted to be as thorough as possible, however it is quite possible, if not likely, there are undiscovered functions.

Please report any strange behavior/discovered functions/editing methods on the to me, the /r/subrosanrc subreddit or by making an issue on github.

Until a more permanent solution is found, you may use this sub for loose, incomplete, and rough modded file posts if you like. 

**PLEASE contact me /u/Defaultplayer001 AKA Star-LoRed on Steam directly with any questions ! I'm not only ecstatic to help, but your feedback can directly impact the quality of this patch and associated documentation!**

#**rosedit**

Welcome to the rosedit readme.txt! These are unofficial patched Sub Rosa executables that enable a built in editing mode. Nearly all copies of Sub Rosa already have editing mode embedded inside them, they just havent been enabled.

On behalf of all [srs] ,I hope you enjoy!

#**Credits**

/u/hontro for finding editing mode and patching the executables.

Star-LoRED (/u/Defaultplayer001) for writing an in-depth documentation for editing mode and work in the patch.
#**Supported versions**

0.25
####**Important Note**

The download link is hosted separatley from GitHub for security reasons. The modified executables are the sole property of Cryptic Sea, and are to be used for educational purposes only. We are not responsible and do not condone any malicious activity attempted with these modified executables.

#**Installation**

Simply place each executable in your Sub Rosa root directory.

It should be in C:\Program Files (x86)\Steam\steamapps\common\Sub Rosa

#**Download**

(to be linked)

Note on custom textures: The editor will load any textures of the right file type/size located in the /data/textures directory. So fully custom textures ARE possible. However, it is not as simple as click to add, it's really finicky, but there is a method. I will research more and post a reliable method.

#**Main Menu Hotkeys**

**E**: Editor

**D**: Practice

**S**: Start

**U**: User list? NOT RELEVANT INFORMATION FOR EDITING IGNORE

**O**: Options

#**In-Person Controls For Both Modes**

Basic movement is, of course, the same as Sub Rosa defaultt.

If unfamiliar, all you really need to know for the editor is:

WASD: Movement
Mouse: Camera controls
E: Enter Vehicles

**6**: Freecam

Controls:

**W**,**A**,**S**,**D**: Movement Hold Right mouse button to look around. 

**Q**: Up 

**Z**: Down

**7**: Original body

**8**: AI body 1 if available

**9**: AI body 2 if available

**0**: AI body 3 if available

**+ & =**: Toggles the "Press F1 to toggle help" text.

**``I``**: Slow-mo

**O**: Toggle pause

**P**: Pause simulation

**K**: Render shadow maps

**[ & ]**: Adjust day/night cycle

**,**: Editing info(?)

**X**: 3rd-person camera

**B**: Render every phsyics affected object in wireframe

**F5**: Refresh map

**F6**: Render the entire scene in wireframe mode

**F10** Cheat Toggle, spent hours trying to figure out what this does, can only find that it modifies the "Cheat" toggle value in an F11 information page. PLEASE tell me if you find out anything this changes. 

**F11**: Cycle through various editing information

#**Editor**

Funtion key tools: Press F1 to enter the function tools "menu" then F1-F6 for editing tools, detailed below.

#**F1: Block tools**

**``1``**: Block

``Y``: Toggle floor

``2``: Interior Spec

Left click anywhere to place a block, right click to delete. 

Click the blank space in the middle of the right hand panel, then Mouse-wheel to scroll through imported objects.

Same as before, left click to place, right click to delete.

Mouse Wheel through the blocks on the right hand to cycle through appliied textures on objects, I'll go through and figure this out exactly later, I've learned it by "feel". Sorta annoying. Will only cycle through textures imported under the 

[ & ]: Palette tools, cycle to apply a color filter to the selected texture.

3: Exterior Spec

Same as above, haven't worked out how the differ exactly, but, some models seem to display odditites if placed under one and not the other.

**F2: Edge tools**

        1-0, select model to place.
        Left click to place, Right click to delete
**F3: Area**

    Seems to set base's hire area+hosptial healing area. Further testing needed.
    Click+drag to set area
**F4 :Objects**

    Seems to control AI building disc spawn location. Further testing needed.
**F5: Textures**

    Select a texture from lower section, and click import to add to the current building's available textures.
    You can also delete them from the available tiles, but I've yet to find a compelling reason to ever do this. Presumabley you will       eventually run into memory issues.
**F6: Models**

    Select a Model from lower section, and click insert to add to the current building's available tiles.
    You can also delete them from the available tiles, but I've yet to find a compelling reason to ever do this.
**R**: Up 1 level

**F**: Down 1 level

**-** & **=**: Block type too, All of them but

Key's next to 0, for extra clarification, *not* numpad.
**Practice Mode**

Funtion key tools: Press F1 to enter the function tools "menu". Then F1-F3 for editing tools, detailed below.

**F1: Street Tools**

Left click anywhere to place a street corner, represented by a green dot, after placing one, place another that is parallel to create a street.

You can also do this by left clicking on a previously placed green dot, then again, placing another parallel.

Left click on the newly created street, by default named "Street" to bring up a text field in the right-hand side that you can use to edit the street name.

Right click green dots to disable them.

**F2: Sidewalk Tools**

Left click a model type to place, right click to delete.

Modifiers, hold then left click like normal:
1-4: Small sidewalk ramp, Various directions. Only works on the "Sidewalk" model.

5: Grass

6: Asphalt

7: Pillar. Only works on the "Sidewalk" model.

**F3: Building tools**

Left click on the building you want to place.

**Hold E**: Ready placement, press left mouse button to place.

**R** & **F**: Cycle through building types, the list will not show them all, so you will have to use the cycle keys to select all building types.

**T**: Rotate


