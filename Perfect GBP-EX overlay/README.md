After my GBC overlay, I looked back at my DMG version and noticed some aspects that could be improved. Although this new overlay does the same thing, it has been created from scratch, taking advantage of some tricks I learned when creating the GBC overlay. The result is a more polished and realistic version.

Changes:

Improved dot matrix realism.

Improved sharpness.

Improved brightness.

A new color scheme with improved accuracy.

It has been tuned with a real GB DMG alongside a MM+ and is meant to be used with the same color settings I recommended with the GBC overlay: 7-10-14-18. That way with a low brightness setting, the sharpness and colors match a real DMG in a bright daylight environment (with just level 2 of brightness already gives a very realistic look, so don't go crazy increasing too much the brightness!) .

I always found the embedded DMG color setting to be a little off, not like I remembered playing a GB DMG. With this overlay I took a different approach and created a custom color palette, that way I have complete freedom to choose what I want. I chose the colors from a real GB DMG and adjusted them until they looked as expected on the MM+ screen. So this overlay works together with an additional file with the color data that you need to copy to your SD.

To configure: (under Onion)

-Download all the files: https://drive.google.com/drive/folders/1Q3AvZl4oB1zY1nlCt3RO1wVRPQWoXIjH

-Copy "Perfect_DMG-EX.png" and "Perfect_DMG-EX.cfg" to this path in your SD: RetroArch/.retroarch/overlay/GB-GBC/

-Copy "default.pal" to this path in your SD: BIOS/palettes/

*Note: in the folder there's already a file with the same name, you can overwrite it with my file or rename the old file before copying my new file, in case you want to revert the changes for some reason. And if you don't see any folder named "palettes" in BIOS/, create a new one with that exact name and copy the "default.pal" file inside.

-During a game: Menu+select > On-Screen Overlay > Overlay Preset > GB-GBC > Perfect_DMG-EX.cfg

-Go back to "Core Options":

GB Colorization > custom / external file

Interframe Blending > Simple (Note: Don't use any of the "LCD Ghosting" presets as they produce additional graphical artifacts in dark areas)

Manage Core Options > Save Content Directory Options (Note: if your only options is: "Delete Content Directory Options", don't select any option and go to the next step, it will autosave)

-Go back to "Settings" > Video > Scaling > Integer Scale OFF, Keep Aspect Ratio ON

-Go back to "Image Interpolation" > Bicubic

-Go back to "Quick Menu" > Overrides > Save Content Directory Overrides

-Go back and "Resume" the game.

Enjoy.