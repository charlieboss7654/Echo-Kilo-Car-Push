# Vehicle Push Script

A lightweight FiveM script that allows players to push vehicles manually. Designed for realism and immersion, the system supports both car and bike pushing, using a combination of `ox_target` and 3D text prompts depending on vehicle type.

## Features

* Supports **addon and base game vehicles**
* Vehicles use **`ox_target` third eye** prompts (at the trunk)
* Press **X** to stop pushing and return to normal position
* Prevents pushing of **military, aircraft, lorries, and trains**
* Smooth animation and realistic push behavior

## Dependencies

* ox_target - https://github.com/overextended/ox_target

## Installation

1. Place the script folder in your server’s `resources` directory.

2. Add the following to your `server.cfg`:

   ensure EKS_CarPush
   

3. Ensure `ox_target` is also started in your server.


## How to Use

1. Walk near the trunk of any car.
2. Hover over the trunk using `ox_target`.
3. Click the **Push Vehicle** prompt.
4. Use **W/S/A/D** to move or steer the vehicle.
5. Press **X** to cancel and detach.

## Notes

* The script prevents pushing large, unrealistic vehicles such as planes, trains, boats, lorries, and military vehicles.
* Addon vehicles are supported as long as they include proper bone mappings (`boot` for trunk).

## DO NOT CHANGE THE NAME OF THE SCRIPT FOLDER - DO NOT CHANGE ANYTHING IN THE FXMANIFEST OR THE SCRIPT WILL NOT WORK

Support:
https://discord.gg/busQ9w6dqa
