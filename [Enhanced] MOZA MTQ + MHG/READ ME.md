# Sub's Currated Bindings - MOZA MTQ Throttle + AB6 FFB + MHG Grip

> [!WARNING]
> THESE BINDINGS REQUIRE JOYSTICK GREMLIN!

> [!NOTE]
> My binds are now open source. I need contributers to assist with small updates when a patch drops. DM me on discord if you are interested. <https://github.com/SubliminalsTV/Subs-Curated-Bindings>

## Navigation

- [Install Videos](#instalation-video-guides)
- [Known Issues](#known-issues)
- [Functions](#functions)
  - [Freelook](#freelook)
  - [Eye Tracker Targeting](#eye-tracker-targeting)
  - [Moza Cockpit Settings](#my-moza-cockpit-settings)
- [Text To Speach & Audio Files](#adding-text-to-speach--audio-files)
- [Troubleshooting](#troubleshooting)
- [Binding Charts](#binding-charts---no-more-adobe)

## Instalation Video Guides

At the time of making these video guides I had not yet distributed MOZA Binds. These guides have little to do with the joysticks themselves so these videos are just fine to demonstrate how to set them up regardless of what sticks you use.

### vJoy Install Video

vJoy Install Video - <https://youtu.be/ugjgKPf1-rk?si=nWBojuAKDvjGu3LO>
> [!WARNING]
> Check 3rd video for vJoy settings!

### HIDHide Install Video

HIDHide Install Video - <https://youtu.be/PyL156AywYQ?si=4XSdzWdzmITRkMPi>
> [!WARNING]
> Check 3rd video for HIDHide settings!

### Joystick Gremlin

Loading Enhanced Binds - <https://youtu.be/mc-ozIogrpI?si=WuwMqg0S-G922i10>
> [!WARNING]
> Assumes you have vJoy, HIDHide, and JG installed!

## Known Issues

### MFD Binds

- MFD Binds do not import properly into Star Citizen, this is a bug. They also have to be cleared manually to remove them. So you will need to add them manually, but hopefully they should stick after that.
- I have attached images with the binds that need to be added. They are all AB6 Base button binds.
- Please contribute to the issue council report. <https://issue-council.robertsspaceindustries.com/projects/STAR-CITIZEN/issues/STARC-133477>

### Broken SC Binds

The following binds seem to be broken currently in 4.5... welcome to Star Citizen

- Sometimes staggar fire doesnt load may need to load it manually

### ABS Axis - Ship wont take off?

- I have various axis that are set to aabsolute. Some are bound to critical things like how much engine power your ship uses (Acceleration Limiter) etc. If you leave one of these in the down position then your ship may not take off or you might have some other issue. In the past I have had these bound and people flooded the forums complaining their sticks wouldnt work. But their child had just come into the room and started pulling levers. ROFL. I am adding them back becuase they are useful but if I keep getting comments then ill remove them in a future patch. This is why you guys cant have nice things becuase you are the only people who read the FUCKING READ ME!!!

## Functions

### Freelook

To use freelook. Go into 3rd person (up on the throttles `Smallest-4-Way-Hat`). Now you are free to look around using the `R-Ministick` Click and HOLD in on the `L-Bottom-4-Way-Hat` to reset view.

### Eye Tracker Targeting

The main way I Target in Star Citizen is via an Eye Tracker. This adds to immersion and is a lot easier than using the native binds. Just look at the target, press a button and then they are locked. There are two eye trackers I recommend.

- Tobii Eye Tracker is next generation head and eye tracking. Unlock unique features that deepen your level of immersion in your favorite games including Star Citizen, Microsoft Flight Simulator, DCS, and more.

  - For more info and 5% off visit <https://tobii.subliminal.gg> "Purchases using the link and code `subliminal` at checkout support the curration of these binds."

- For a more budget friendly alternative check out Beam Eye Tracker. It is software only, and does require you to use your own webcam. It has some limitations like playing in a dark room or seeing through your glasses. But if you have a webcam and want to try eye tracking this is a MUST HAVE. There is a free trail on steam. Or you can buy it directly from beam.

  - For more info visit <https://beam.eyeware.tech/?via=subliminal> "Purchases using the link and purchasing through Beam directly support the curration of these binds."

### My Moza Cockpit Settings

Some of my Moza Cockpit settings will have to match yours for these binds to work properly.

#### Grip

- Make sure to Calibrate Both `Cogging Torque` and `Axisd Calibration`
- Grip Settings: Mode 1 `Button Mapping` Mode 2 `Axis Mode`
- `Press stick to switch mode`: On

#### Throttle

- Calibrate the Ministick
- Calibrate the Throttle and follow the directions. Make sure to hold throttle gate up all the way the entire time.
- Throttle Detent Setup: First make sure Detent Button Mapping is on. Make sure to calibrate idle while the throttle is completely down past the throttle gate. And calibrate the after burner with the throttle pressed firmly up against the afterburner gate. I pressed it firm enough that it is farther than I would during play but not firm enough to do damgage to the throttle. For example at the after burner gate I am at 78% I pussed it to about 80%. Feel free to left the gate if your not comfortible pressing firmly.
- Finally my afterburner position is at 80% same as what I calibrated the afterburner gate for.

## Adding Text to Speach & Audio Files

To ensure joystick gremlin and Star Citizen modes are synced I prefer to have JG use TTS or play a sound clip when I switch modes. By default I have included TTS prompts. If you prefer audio files I have some included in the download.

### Adding Audio Files

- In the upper right hand corner of JG, you can select which mode you would like to edit. In the `SCM Mode`, the MTW Throttle has a 5 position knob that presses `Button 17` through `Button 21`. Button`Button 17` `Button 19` and `Button 21` switches Master Modes Nav, SCM, and Mining/Salvaging (Auxiliary). To add the audio files you will need to add an action for `Play Sound` to each of these three mappings.

- To add the provided audio files, click `Button 17` in Joystick Gremlin then look towards the bottom of the action panel underneath the last action. Click the remap drop down and select `play sound`. Then click the `Add` button next to it. Clicking the pencil button will allow you to use windows explorer to tell JG where to find the audio files.

- There are multiple options for what audio files you can use and of course you could use your own. The audio files I provide are either voices from "Computer" aka/LCARS from Star Trek or HAL9000. And HAL9000 has two variations of dialogue.

- The Salvage and Mining audio files are for those who only mine OR salvage and want to hear a more personalized message. Auxillary is for those who mine and salvage. (This has no effect on the binds or game.)

- Simply load the .wave audio file for the corresponding mode. To know which one to use just read whatever I have in the Cycle Modes long press box inside JG.

- Remember to do this for `button 19`and `button 21` in for the MTQ Throttle only

> [!WARNING]  
> You must save the JG profile after making changes to avoid having to repeat this every time JG or your PC restarts. It is a good practice to `Save As` and not overright my original JG file incase you may need to reload that working one in the future.

> [!WARNING]  
> Best Practices: You must have text or at least a `space` in the TTS box or else it will cause issues with JG. And the audio files must be linked properly, if you move them later not only will they not play but JG has issues when you have broken links in these fields.

### Removing Text To Speech when cycling modes

There are multiple ways to remove text to speech if you prefer not to hear it.

- The easiest way is to reduce the volume in `Windows Volume Mixer`if you prefer not to mess with JG at all.

- If you would like to remove it from JG, In the upper right hand corner of JG, you can select which mode you would like to edit. In the `SCM Mode`, `Aux Mode`, and `NAV Mode`, the VMAX Throttle `Button 21` cycles Master Modes and `Button 23` cycles in and out of Mining/Salvage Modes (Auxiliary). To remove TTS you can just click the `X` on this box.

- Remember to do this for `button 17`, `button 19` and `button 21` for the MTQ Throttle only

> [!WARNING]  
> You must save the JG profile after making changes to avoid having to repeat this every time JG or your PC restarts. It is a good practice to `Save As` and not overright my original JG file incase you may need to reload that working one in the future.

## Troubleshooting

Common Enhanced bind issues and their fixes can be found in the FAQ In Discord

- <https://discord.com/channels/303670222097874945/1297919077062279209>

Common Joystick/Star Citizen related issues and their fixes can be found here

- <https://discord.com/channels/303670222097874945/1154143410215731201>

> [!TIP]  
> If you have an issue not found in either of the FAQs, please read and follow the simple instructions in the pinned post in the [Enhanced Bindings Support Forum](<https://discord.com/channels/303670222097874945/1006954369800998992>) before posting your question or concern.

## Binding charts - NO MORE ADOBE!!!

I have finally escaped Adobe's firm grasp and now moved the the free, fully featured alternative, Affinity. [https://www.affinity.studio/get-affinity](https://www.affinity.studio/get-affinity)
Affinty is now FREE!! Meaning anyone can open the .af files and edit them.

### Printer Friendly Binding Chart

- The chart labled `[Print]` has a white backgound to conserve ink for people who would like to print it.

- PRO TIP: If you have the paid version of adobe acrobat you can open the PNG file inside it and select the "Poster" option in the print settings and change the scale from %100 to 30% and it will spplit the chart into two pages with 1 stick on each page. For other programs just remember that scalled down to 30% its small enough to fit each stick on its own page.
