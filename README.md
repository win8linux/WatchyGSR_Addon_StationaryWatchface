# Stationary Text watchface for Watchy GSR

![Stationary Text watchface](stationary.png)

A port of the [Stationary Text](https://github.com/BraininaBowl/Stationary-Text-for-Watchy) watchface first made by BraininaBowl for the original Watchy firmware to [Watchy GSR](https://github.com/gurusr/Watchy_GSR). Based on the Stationary Text watchface for Pebble, but without sliding text.

## Adding to a Watchy GSR build
1. Add this repo as a submodule in a Watchy GSR repo:
```sh
git submodule add https://github.com/win8linux/WatchyGSR_Addon_StationaryWatchface.git "Watchface Addons/Stationary"
```
2. Add the following include to `src/GSR.ino` in Watchy GSR:
```cpp
#include "../Watchface Addons/Stationary/StationaryText.h"
```
3. Compile!
