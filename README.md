# ED-Control-Noodling
Noodling around with some (built-in) Elite Dangerous features to try to figure out how to make a smart control binding app.

## Installation
The `DeviceMappings.xml` and `ThrustMasterHOTASViper.binds` files go into `%SteamLibrary%\steamapps\common\Elite Dangerous\Products\elite-dangerous-odyssey-64\ControlSchemes`.

The files in the `DeviceButtonMaps` folder go into the `DeviceButtonMaps` folder inside that `ControlSchemes` folder.

Everything is very much still a work in progress (although it might turn into a lot of nothing).

## List of USB IDs

If you want to add a device to DeviceMappings.xml, the binds for it into a Binds XML into ControlSchema, and/or the button maps for it into DeviceButtonMaps, you're going to need a list of which USB Vendor IDs and Product IDs are used by your device.

I don't maintain such a list, but they're available; I had to hunt one down, which took longer than I wanted.

Here are some details from and about the list I found:

```txt
    Maintained by Stephen J. Gowdy <linux.usb.ids@gmail.com>
    If you have any new entries, please submit them via
        http://www.linux-usb.org/usb-ids.html
    or send entries as patches (diff -u old new) in the
    body of your email (a bot will attempt to deal with it).
    The latest version can be obtained from
        http://www.linux-usb.org/usb.ids
```

## TODO

A Preset name seems to be a human-friendly name pointing to Binds XML file. How do I make a Preset name with spaces in it?
