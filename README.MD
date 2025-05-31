This repo contains Fritzing parts and other resources for use in Harp documentation. It is organized in this way:

## Folders

- `Parts` - Contains fritzing components. 
- `Sketches` - Contains fritzing sketches.
- `Images` - Contains illustrations or images for parts which have no corresponding fritzing component. Usually taken from vendor website. To be used for either creating new fritzing parts in the future or making composite output images.
- `Composites` - contains overlaid fritzing/illustrations output. 
    - So this is a bit crazy, I have tried to make the image compositions in `Gimp` but for some reason they always come out either soft or jaggy with uneven lines. I suspect this has to be with the interpolation during scaling, but even disabling it does not improve. For that reason, for now, I am overlaying them in `Powerpoint` (horrible, I know) but there is some magic there that preserves the image quality. Any other image editor suggestions that work better are much appreciated.

### Subfolders

When present these folders contain the follow items:
- `exported` contains the raw image export from the program (e.g. fritzing).
- `edited`  contains touched up images together with the `Gimp` image editor *.xcf save file.

## Table of available parts

| Part | Image Source | Comment |
| ---- | -------------------- | ------- |
| Pico | [Official Pico Documentation](https://www.raspberrypi.com/documentation/microcontrollers/pico-series.html) | Seems ok but not used currently | 
| Pico H | [Official Pico Documentation](https://www.raspberrypi.com/documentation/microcontrollers/pico-series.html) | Does not export correctly as SVG so exported as PNG |
| Pico 2 | [Official Pico Documentation](https://www.raspberrypi.com/documentation/microcontrollers/pico-series.html) | A lot of detail missing, may not be useable | 

## Table of missing parts

For the [Harp Hobgoblin](https://github.com/harp-tech/device.hobgoblin) tutorials and course, the DFRobot parts (Gravity Shield, Sensor Kit) are not available as Fritzing parts as the official [DFRobot Fritzing library](https://github.com/DFRobot/Fritzing-library) was abandoned (May 3rd 2012). 

Unofficially, there is a [fork](https://github.com/RAPTOR7762/Fritzing-library/tree/master) with some parts, but it does not have  what we need. Furthermore a search was done on the Fritzing [#parts-submit](https://forum.fritzing.org/c/parts-submit/23) as well as the DFRobot [forum](https://www.dfrobot.com/forum/search/fritzing) for user contributed parts.

For these missing parts, I have collected images that we can use in the future to build fritzing parts or overlay for fritzing sketches (if its not too weird).

| Part | Image Source |
| ---- | ------------------------------------ |
| Gravity Expansion Shield (DFR0848) | [Official Product Page](https://www.dfrobot.com/product-2393.html) | 

