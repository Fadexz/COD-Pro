A script designed around making timings fast and precise so you can execute features at a fast pace.
It also has lots of features made by myself, and is highly customisable for how you want to play.
It also aims to be simple and easy to navigate!
The script involves thousands of hours of work, quality and care to make it all come together made to the best of my ability 😰

This script includes randomised and speed limited values, so you can be sure it will be safe to use in case you are worried about some kind of detection (however it shouldn't be something to worry about, you can disable these) 😎

Please contact me for any questions, suggestions, or issues, I value your feedback!
Best place to contact me is on Discord, however you can use the forum as well
https://discord.com/users/291872132898619392 (fadexz)

If you would like to be generous, you can support my efforts to focus on putting out better and more scripts in the future and hopefully keep going 🥵
https://revolut.me/Fadexz
https://www.buymeacoffee.com/Fadexz (note: sent internationally)
https://paypal.me/Fadexz

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
[Added] Multiple new screensaver options 
[Added] Quick Scoper ADS + Lethal activation mode
[Added] Menu Border highlight options
[Added] More LED Config LED display options
[Added] Controller Inactivity Timeout (turn off controller is wireless only)
[Added] Fast Power Off mod which allows you to do a configurable hold of time to turn off your controller (can be turned off faster) (wireless only)
[Added] Adaptive Triggers Config - Able to controller what the adaptive triggers do, gives full customisation of values (not dynamic currently)
[Added] No Rumble Fix for DualSense (useful on PC to fix vibration breaking mostly with legacy games which need you to output as an XInput / Xbox 360 Controller instead)
[Added] Visual notification for Rapid Fire Quick Toggle change
[Added] Donation position in the 'mod' menu to easily know how you can support
[Added] Now able to disable / turn off the LED customisations
[Added] Rapid Fire Hold option - Should allow for shots to be ready to fire instantly more often and is most useful for when you match the speed of your weapon's fire rate or a little bit higher so that very little time is spent off the trigger and mostly holding, waiting for the weapon to be ready to fire
[Removed] Steady Aim (reduces aim angles) - If you would like me to add this back in just send me a message, however I didn't find it useful
[Adjusted] Values that were hidden within unrelated mods have now been moved into their own space in the 'mod' menu
[Adjusted] Many default values adjusted to best suit use for MWIII (wow... it really has been that long)
[Adjusted] The "AIM" button is now referred to as 'ADS' in the script to match the game's description
[Adjusted] Scrolling Text default timing values and tweaked how it scales slightly
[Adjusted] Title Screen Title now dismisses after 50 seconds of the script running
[Adjusted] Changed the names of some mods
[Adjusted] Display sleep time from 1 minute to 2 minutes
[Adjusted] Script VM Timing will now default to 2ms instead of 1ms (before a controller is connected)
[Adjusted] Splash Screen display and display timings
[Adjusted] Value repeat on hold increment functionality changed, it will now change by multiples after holding for 3 seconds
[Adjusted] Menu Rumble FX - A Rumble Motor value slightly increased
[Adjusted] 'Main' Menu selected visual style changed
[Fixed] CPU limit being reached when quickly changing options (holding), the screen will no longer flash and it won't hit the CPU limits
[Fixed] Minor fixes to prevent wait times possibly being lower than intended on turbo related features
[Fixed] Turbo related values with the limited values option enabled could cause the minimum value to not be correct when the Input Interval option was changed

Current Known Minor Issues:
- This script may not work great with controllers running at 100hz, this would include Xbox Bluetooth connection, PS3 Controllers, and possibly others with Bluetooth connections that max out at this polling rate. This script will run in intervals of 2ms from 8ms, 4ms, or 2ms. I will update the script later to automatically detect the real polling rate instead of per platform and support for handling controllers of 10ms, you can workaround this by setting the Input Interval to something like '22' or '18' for the time being which will set it to 2ms which is a divisor of 10ms (100hz).
- When you use randomisation you should expect extra delay to be added to the speed you set for the input times, so it will be slightly slower than specified, I may change this later to be averaged
- LED will not change back to full brightness when it is changing from "breathing" on the 'Battery Status' mode
