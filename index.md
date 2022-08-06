---
layout: default
title: Big Angular Flight Picture Mode
---

# Big Angular Flight Picture Mode

_Mr. Angular Velocity's [Steam Controller bindings for Elite: Dangerous](https://www.reddit.com/r/EliteDangerous/comments/e618ml/steam_controller_elite_detailed_configuration_a/), modified to support FA-off and Odyssey_

### [Reference Card](https://docs.google.com/spreadsheets/d/1Kq_-igWF8gBGCXUd-xO4WzAUgmmJgPT9XFkpKyXXNZw/)

# Installation

1. Copy [Big Angular Flight Picture Mode.3.0.binds](Big Angular Flight Picture Mode.3.0.binds) and [Big Angular Flight Picture Mode.4.0.binds](Big Angular Flight Picture Mode.4.0.binds) to `%LOCALAPPDATA%\Frontier Developments\Elite Dangerous\Options\Bindings`.

2. Launch Elite: Dangerous via Steam's [Big Picture mode](https://help.steampowered.com/en/faqs/view/3725-76D3-3F31-FB63).

3. Open the following Steam URI in Windows Explorer: `steam://controllerconfig/359320/2828850007`.

4. Select the **Big Angular Flight Picture Mode** controller configuration via the Steam overlay.

5. Select the **Big Angular Flight Picture Mode** bindings in game.

# Device Mappings

TODO diagram

The Steam Controller combines the behavior of an Xbox 360 controller, a mouse, and a keyboard:
- The analog joystick emulates a clickable left stick.
- The left trackpad acts like a 4-way direction pad (Up/Down/Left/Right).
- The right trackpad emulates a clickable right stick.
- Touching the right trackpad moves the joystick in that direction, deflecting more the further from the center it's touched.
- Touching the right trackpad simultaneously activates the gyroscope, which emulates a mouse.
- The face buttons act like a second 4-way direction pad (A/B/X/Y).

# Basic Flight

TODO diagram

All six degrees of freedom are accessible from the controller:
- The left stick (analog joystick) controls _pitch_ (tilt forward/backward) and _roll_ (tilt left/right).
- The grip paddles control _yaw_ (turn left/right).
- The right stick (right trackpad) controls _heave_ (vertical thrust) and _sway_ (lateral thrust).
- The triggers control _surge_ (longitudinal thrust), the main engine's throttle, and the booster.
- As an analog device, a trigger commands thrust proportional to the degree it's depressed.
  The right trigger controls forward thrust; the left, backward.
- When a trigger is pulled to the stop but not clicked (a soft pull), it will increase (right trigger) or decrease (left trigger) the throttle for as long as the trigger is held.
- Soft pull both triggers together to zero the throttle.
- Double soft pull the right trigger to boost.
Additional actions are described in [Advanced Flight](#advanced-flight).

TODO diagram

Likewise, all ship functions are accessible from the controller:
- The direction pad (Up/Down/Left/Right) controls the power distributor.
- The left stick click targets objects in front of the ship.
- The shoulder buttons handle fire control.
- The face buttons (A/B/X/Y), the Back button, and the right stick click modify the behavior of the other controls.
- A button combos trigger ship utility modules, e.g., press A plus Left to use a heat sink.
- B button combos activate the user interface, e.g., press B plus Up to access comms.
- X button combos control weapon systems, e.g., press X plus Right to engage or disengage silent running.
- Y button combos manage targeting, e.g., press Y plus Left to select the previous target.
- Right stick click combos access wing (team) functions, e.g., press the right stick plus Left to select the first wingmate.
- Back button combos access utility functions, e.g., press Back plus Right to open the galaxy map.
Refer to the reference card for a complete list of button combinations.

# Advanced Flight

Touching the right trackpad activates the gyroscope, which controls _pitch_ and _yaw_ via mouse emulation.
The in-game bindings enable relative mouse movement with the maximum possible decay rate.
Use the gyroscope for very fine control over ship attitude.
This is specifically intended for use with **flight assist off**.
Use the left stick and grip paddles for gross attitude control with **flight assist on** or in supercruise.
Toggle flight assist by pressing both grip paddles together.
Toggle rotational correction by pressing A plus both grip paddles.

Clicking and holding the right trackpad activates mouselook using the gyroscope.

Press and hold the Back button for a little more than three (3) seconds to toggle the **Macros** action layer.
You will hear a beep and feel the controller vibrate when the action layer is activated or deactivated.
(The Steam overlay will not always show visual confirmation of the change due to a bug.)
When the action layer is active, use the following key combinations to set the power distributor to one of four presets:
- Hold Left, then press Left to set the distributor to 4-2-0.
- Hold Up, then press Up to set the distributor to 2-4-0.
- Hold Right, then press Right to set the distributor to 0-2-4.
- Hold Down to set the distributor to 0-3-3.

# User Interfaces

Navigate all menus using the direction pad.
Some interfaces can be navigated using the left stick or gyroscope (mouse).
Select menu items with the A button.
Exit menus with the B button.
Switch tabs using the shoulder buttons.
In chat, the Back button and the grip paddles change channels—local, system, squadron, etc.

Pressing the Start button displays a virtual keyboard.
Use the left and right touchpads to select symbols on the keyboard, and click the corresponding touchpad to type the selected symbol.
Exit the virtual keyboard by pressing the B button or clicking Done.
Press A plus the left stick to paste text from the clipboard.
This can be used to paste destinations into the galaxy map search box or canned responses into the text chat.

Holding the Start button pauses the game (sends the Escape key).

# Map Views

In the galaxy and system maps, the left stick (left/right) or the grip paddles (up/down) pan the camera.
The triggers control the camera zoom.
The right stick controls the camera pitch and yaw.

In the Full Spectrum System Scanner (FSS), TODO

In the Detailed Surface Scanner (DSS), TODO

# Multicrew

The ship-launched fighter uses controls similar to those described above.

The idle/gunner role makes the following changes to the controls:
- Some controls are not available to crew members, e.g., ship movement.
- Press the A button to switch turret modes.
- Press Down to switch cockpit UI (radar display) modes.
- Use the triggers to activate the primary (right trigger) and secondary utilities (left trigger).

# Driving

TODO

# On Foot

TODO
