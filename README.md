# -TES3MP-resources

## Introduction
Modules and files that provide additional data for use in scripts are stored here.

## Installation and use
1. Download these to the folder */server/scripts/custom/*
2. Either download scripts that already require them (see below) or require them inside your own

## Descriptions

### dimensions.lua
- module that provides dimensions for over 9000 objects
- has been optimized so that there's no dimensions duplicates and objects with the same dimensions refer to the first occurence
- *format:* dimensions[refId] = {x = float, y = float, z = float}
- used by edited [kanaFurniture](https://github.com/Nkfree/tes3mp-scripts/blob/master/0.7/kanaFurniture/kanaFurniture.lua) and [decorateHelp](https://github.com/Nkfree/tes3mp-scripts/blob/master/0.7/decorateHelp.lua)

### locations.lua
- module that consists of exterior cell ids mapped to their string representation
- *example:* locations["-3, -2"] = "Balmora"

### namesData.lua
- module that consists of refId-name pairs
- *format:* namesData[refId] = name
- used by [playerKillCount](https://github.com/Nkfree/-TES3MP-playerKillCount)
