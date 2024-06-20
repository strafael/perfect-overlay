After my DMG overlay, a GBP petition came up. I was asked if it would be possible to render a realistic GBC screen with an overlay, so I finally accepted the challenge since most of the GBC shaders and filters existing were a far cry of the real screen.

This one was HARD. I spent more time creating this than all of my previous overlays combined. The GBC which has a non-backlit reflective screen is unique in the way the pixels are displayed. The original colors largely depend on the amount of ambient light and its color temperature.

I tried to replicate the original GBC experience, but in ideal conditions, with the perfect angle and brightness, but this is a dark overlay, even if it can look much brighter than the original screen ever would. The way you increase the brightness will simulate the intensity of the light source on the real screen, so even at maximum brightness don't expect a blinding screen because it is quite dim and has the original pale colors of the real GBC. If you don't like this, I recommend using this color setting in the MM+: 7-10-14-18, it brings more brightness and color to the games (all my photos are with this setting). It's also a good setting to use with any other overlays that darken the image, such as Perfect_CRT-240p.

Features:

Full screen RGB subpixel simulation.

Real GBC colors.

The most accurate way to play GBC in a 480p screen.

To configure:

First of all, if you are using my previous DMG overlay, launch a GB game and go to: Core Options > Manage Core Options > Save Content Directory Options

That will avoid any interference between the GB and GBC settings, as they share the same core. Now you can start the GBC configuration:

-Download all the files: https://drive.google.com/drive/folders/1apPNS0hBm9LxLLyACs5YAVmHmqxE01FA

-Copy all them to this path in your SD: RetroArch/.retroarch/overlay/GB-GBC/

-During a game: Menu+select > On-Screen Overlay > Overlay Preset > GB-GBC > Perfect_GBC.cfg

-Go back to "Core Options":

GB Colorization > GBC

Color Correction > GBC Only

Color Correction Mode > Accurate

Color Correction - Frontlight Position > Above Screen (lighter, for more realistic GBC colors) or Central (darker, for more vibrant colors and inky blacks)

Interframe Blending > Simple

Manage Core Options > Save Content Directory Options

-Go back to "Settings" > Video > Scaling > Integer Scale OFF, Keep Aspect Ratio ON

-Go back to "Image Interpolation" > Bicubic

-Go back to "Quick Menu" > Overrides > Save Content Directory Overrides

-Go back and "Resume" the game.

Enjoy.