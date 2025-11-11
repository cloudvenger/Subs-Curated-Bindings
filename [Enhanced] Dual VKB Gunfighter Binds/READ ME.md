# READ ME

> [!CAUTION]
> THESE BINDINGS REQUIRE JOYSTICK GREMLIN!

## Instalation Video Guides

At the time of making these guides I had not yet distributed VKB GF Binds. These guides have little to do with the joysticks themselves so these videos are just fine to demonstrait how to set them up regardless of what sticks you use.

### vJoy

vJoy Install Video - <https://youtu.be/ugjgKPf1-rk?si=nWBojuAKDvjGu3LO> *Check 3rd video for vJoy settings*

### HIDHide

HIDHide Install Video - <https://youtu.be/PyL156AywYQ?si=4XSdzWdzmITRkMPi> *Check 3rd video for HIDHide settings*

### Joystick Gremlin

Installing Enhanced Binds - <https://youtu.be/mc-ozIogrpI?si=WuwMqg0S-G922i10> *Assumes you have all the programs installed*

## Troubleshooting

Common Enhanced bind issues and their fixes can be found in the FAQ In Discord

- <https://discord.com/channels/303670222097874945/1297919077062279209>

Common Joystick/Star Citizen related issues and their fixes can be found here

- <https://discord.com/channels/303670222097874945/1154143410215731201>

> [!TIP]  
> If you have an issue not found in the FAQ, please create a post in the "#vkb-support forum" on discord if your issue isn't in the checklist or FAQ. Please mention a @PeripheralExpert to ensure we get a ping ASAP - <https://discord.com/channels/303670222097874945/1006954369800998992>

## Missing MFD Binds

There are binds for navigating through MFDs and MFD pages by using the joysticks. But in true `Star Citizen` fashion there is a bug that doesnt allow those binds to be imported. So even though they are in the XML file they dont get laoded into the game. If you wish to use these binds you will need to manually add them. I have provided a screenshot of what binds are supposed to be bound in the SC settings. Just match the in-game settins to what is in that image.

## Text to Speach & Audio Files

In this update I removed the "play audio file" action from the JG profile and also the Text To Speach feature. It was causing issues for the users that werent using the feature (i.e. having to restart the profile for mode switching to work). If you would like to use the audio files I created, below are instructions on how to add them.

### Adding Audio Files

- In the upper right hand corner of JG, you can select which mode you would like to edit. In the `SCM Mode`, `Aux Mode`, and `NAV Mode`, the left joystick `Button 3` cycles modes. To add the audio files you will need to add an action for `Play Sound` to audibly confirm when JG changes Modes.

- To add the provided audio files, click `Button 3` then look towards the bottom of the action panel underneath the last action. Click the remap drop down and select `play sound`. Then click the `Add` button next to it. Clicking the pencil button will allow you to use windows explorer to tell JG where to find the audio files.

- There are multiple options for what audio files you can use and of course you could use your own. The audio files I provide are either voices from "Computer" aka/LCARS from Star Trek or HAL9000. And HAL9000 has two variations of dialogue.

- The Salvage and Mining audio files are for those who only mine OR salvage and want to hear a more personalized message. Auxillary is for those who mine and salvage. (This has no effect on the binds or game.)

- Simply load the .wave audio file for the corresponding mode. To know which one to use just read whatever I have in the Cycle Modes long press box inside JG.

- Remember to do this for `button 3` in `SCM Mode`, `Aux Mode`, and `NAV Mode` for the left stick only

> [!WARNING]  
> You must save the JG profile after making changes to avoid having to repeat this every time JG or your PC restarts. It is a good practice to `Save As` and not overright my original JG file incase you may need to reload that working one in the future.

### Adding Text To Speech when cycling modes

- In the upper right hand corner of JG, you can select which mode you would like to edit. In the `SCM Mode`, `Aux Mode`, and `NAV Mode`, the left joystick `Button 3` cycles modes. To add TTS you will need to add an action for `Text To Speech` to audibly confirm when JG changes Modes.

- To add the TTS dialogue, click `Button 3` then look towards the bottom of the action panel underneath the last action. Click the remap drop down and select `Text To Speech`. Then click the `Add` button next to it. Then just type what you would like to have the TTS say every time you press `Button 3` in that mode.

- To know what to type just read whatever I have in the Cycle Modes long press box inside JG. 

- Remember to do this for `button 3` in `SCM Mode`, `Aux Mode`, and `NAV Mode` for the left stick only

> [!WARNING]  
> You must save the JG profile after making changes to avoid having to repeat this every time JG or your PC restarts. It is a good practice to `Save As` and not overright my original JG file incase you may need to reload that working one in the future.

## Editable PDF's

No more editable PDFs!!! I have finally escaped Adobe's firm grasp and now moved the the free alternative Affinity. https://www.affinity.studio/get-affinity
And I havent yet found a way to export to PDF but it no longer matters since Affinty is FREE!! If you wish to edit these files it will be much easier inside Affinity than any other software.

## Printer Friendly Binding Chart

- The chart labled `[PF]` has a white backgound to conserve ink for people who would like to print it.

- If you have the paid version of adobe acrobat you can open the PNG file inside it and select the "Poster" option in the print settings and change the scale from %100 to 30% and it will spplit the chart into two pages with 1 stick on each page. For other programs just remember that scalled down to 30% its small enough to fit each stick on its own page.
