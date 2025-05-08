A script designed around making timings fast and precise so you can execute features at a fast pace.
It also has lots of features made by myself, and is highly customisable for how you want to play.
It also aims to be simple and easy to navigate!
The script involves thousands of hours of work, quality and care to make it all come together made to the best of my ability 😰

This script includes randomised and speed limited values, so you can be sure it will be safe to use in case you are worried about some kind of detection (however it shouldn't be something to worry about, you can disable these) 😎

Please contact me for any questions, suggestions, or issues, I value your feedback!
Best place to contact me is on Discord, however you can use the forum as well
https://discord.com/users/291872132898619392 (fadexz)

If you would like to be generous, you can support my efforts to focus on putting out better and more scripts in the future and hopefully keep going 🥵
https://www.buymeacoffee.com/Fadexz (note: sent internationally)

Be sure to read the information near the top of the script file to help you get along smoothly.

I may make another smaller update soon to do some additions, but I wanted to get this update out as I have been working hard on it for months, and it can't wait forever... as usual, lol 😋

Enjoy! 🎉


Features:
 Anti-Recoil (compensates recoil while also able to use rumble/vibration to increase the amount on shots)
 Slowdown Aim Assist Abuse (automatically moves your ads (in small circle) while you are not moving to allow for slowing down when moving towards a target which will favour to their direction)
 Reload Cancel (automatically cancel reload on press of 'ADS' and/or 'FIRE')
 Auto Reload (automatically reload after shooting)
 Jump Shot (jump when pressing 'ADS' and/or 'FIRE')
 Rapid Fire (turbo/spam 'FIRE' for non-auto weapons automatically on hold)
 Auto Focus (automatically focuses (hold breath) while adsing)
 Auto Ping (ping when firing, on a specified time of no firing cooldown)
 Snap On Aim Assist Abuse (for ZM/SP aka PvE modes, don't use on PvP modes)
 Quick Scoper (instantly unscopes and removes shot recoil to make quick scoping feel nicer, requires a throwing knife)
 Turbo Jump (spam on hold)
 Turbo Melee (spam on hold)
 Auto Sprint (has press, toggle, and hold options) + Boosted Auto Sprint Mode (exploit for Black Ops Cold War) (these also make the walk area larger by making the sprint area a little tighter than in-game Auto Sprint, requires auto sprint in-game disabled and preferably use hold mode to allow the script to stop the sprinting)
 Slide Cancel (Quickly cancels your slide midway and stands immediately)
 Pickup Cancel (Cancels out the animation of picking up a weapon to almost instantly start being able to use it)
 Swap Cancel (Cancels out the animation of swapping a weapon as soon as the weapon has been swapped, best when both weapons have similar swap times)
 Dropshot (automatically drops to prone when firing then immediately stands afterwards)
 Crouch Shot (automatically crouches when firing)
 "YY" Cancel (fun feature, cancel the swap animation constantly to jitter the animation for a visual effect, may cause delayed ads)
 Hair Triggers (removed trigger deadzone — any press is 100% input)
 Custom Deadzone (used to add a deadzone to the physical right stick)
 Humanise Inputs (randomise values and limit turbo features to keep closer to human limitations)
 Display Config (configure what displays on the OLED Screen and how it does, such as screensaver options)
 LED Config (customise how the Zen's LED displays)
 Block Vibration (stop vibration to the controller but allow rumble-based features to still work)
 Inactivity Timeout (allows for you to turn off your controller or other stuff when inactive)
 Fast Power Off (quickly power off your controller with a shorter hold of the XBOX/PS button than usual, for wireless connection only)
 Adaptive Triggers Config (gives control over what the DualSense Adaptive Triggers do)
 No Rumble Fix (fix no vibration on the DualSense controller)
 Crossover Mapping (proper mapping for unmatching controllers and consoles)
 Game Input Layout Customisation (map the script to your game button layout)
 All other features with combos (or automated input sequences) have the "Input Interval" and "Dynamic VM Timing" to ensure you get faster combos with no added "input delay" (aka normally running at 100hz or 10ms intervals, currently always ensures a 125hz/8ms or 250hz/4ms polling rate regardless of input interval used)


Version Notes:
What's changed in this version?
[Added] Static menu border option
[Added] "Vibration" Adaptive Triggers mode option
[Added] Auto Close Controller Update Popup (Xbox) feature
[Added] Quick Toggles for ALL features toggles
[Added] Always On Display option
[Added] Screen Timeout option now adjustable in the menu
[Added] Hair Trigger adjustable points + Shift Start Point option
[Added] Fire (no ADS) Jump Shot activation option
[Added] Omni (any direction) game sprint option
[Added] Auto Cook Frag feature
[Added] Underbarrel Jitter (for MWII/DMZ)
[Added] Debug info in the menu (Controller Battery Level, SPVAR Total Bits Used, Peak CPU Usage, Zen Uptime, and Script Uptime)
[Added] Ability to change the interval at which the Input Interval (and VM Time) will be able to step by, so can now use 1ms steps or only 4ms steps for lower CPU Usage directly in the menu instead of inside the file
[Adjusted] HSB LED options are now full resolution
[Adjusted] Adaptive Triggers default values changed
[Adjusted] VM Time does now not get set to 8ms and will lower like it does outside the menu
[Adjusted] Requires the ADS input to be held less (25% from 75%) to enter the menu
[Adjusted] Menu navigation hold interval/step is now slightly faster to update, so you'll move through it slightly faster
[Adjusted] Edit values will speed up by a slightly larger multiple when you long hold
[Adjusted] Turbo input limits are now at 15/sec instead of 13/sec max
[Adjusted] Menu border is now on static by default (as all options pretty are enterable now so less useful)
[Adjusted] Lowered Pickup Cancel delay after holding to pickup, will cancel earlier
[Adjusted] Now have the ability to set most timings to 0ms instead of the lowest interval
[Adjusted] Other minor stuff not worth mentioning

Current Known Minor Issues:
- This script may not work great with controllers running at 100hz, this would include Xbox Bluetooth connection, PS3 Controllers, and possibly others with Bluetooth connections that max out at this polling rate. This script will run in intervals of 2ms from 8ms, 4ms, or 2ms. I will update the script later to automatically detect the real polling rate instead of per platform and support for handling controllers of 10ms, you can work around this by setting the Input Interval to something like '22' or '18' for the time being which will set it to 2ms which is a divisor of 10ms (100hz).
- When you use randomisation you should expect extra delay to be added to the speed you set for the input times, so it will be slightly slower than specified, I may change this later to be averaged
- LED will not change back to full brightness when it is changing from "breathing" on the 'Battery Status' mode
- Script Uptime value will not show the correct value often (will probably fix in the next update)
- None screensaver option does not clear the screen after a short time (do not use this option for now)
