# ED-Control-Noodling
Noodling around with some (built-in) Elite Dangerous features to try to figure out how to make a smart control binding app.

## File Formats
Both `*.binds` and `*.buttonMap` files are in fact just regular ol' XML. I have opinions about the structure of this particular XML. I've already said too much.

## Installation
The `DeviceMappings.xml` and `ThrustMasterHOTASViper.binds` files go into `%SteamLibrary%\steamapps\common\Elite Dangerous\Products\elite-dangerous-odyssey-64\ControlSchemes`.

The `*.buttonMap` files in the `DeviceButtonMaps` folder are really the crux of the biscuit. These are mappings between standardized "machine readable" axis and button names and useful "human readable" names (and icons). 

I haven't quite figured out the icons yet, except to tell you to check the `Readme.txt` in the official `DeviceButtonMaps` folder. I may have more to say later on the topic of viewing / previewing the icons. I can't find them in a readily accesible cleartext form in the official binaries (yet).

Those aforementioned Button Map XML files go into the `DeviceButtonMaps` folder inside that `ControlSchemes` folder you pasted (or hopefully carefully merged) the Device Mappings XML file and the example Binds XML file.

Everything is very much still a work in progress (although it might turn into a lot of nothing).

## TODO
A Preset name seems to be a human-friendly name pointing to Binds XML file. How do I make a Preset name with spaces in it?
