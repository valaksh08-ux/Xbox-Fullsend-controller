# Gamepad Viewer Xbox Purple Dragon / Sakura Skin

This package is made for GamepadViewer.com's Xbox One skin.

Files:
- xbxsim.css
- skin-overlay.png

## Why it remains functional

The CSS does not replace Gamepad Viewer's live input elements.
It only adds the supplied artwork over the original Xbox shell.
ABXY, analog sticks, D-pad, bumpers, triggers, View/Menu and pressed states
remain controlled by Gamepad Viewer.

## Host it

Upload BOTH files into the same folder on a public HTTPS host.
GitHub Pages is a straightforward option.

Example:
https://YOUR_USERNAME.github.io/YOUR_REPO/xbxsim.css

Then use:

https://gamepadviewer.com/?p=1&editcss=https%3A%2F%2FYOUR_USERNAME.github.io%2FYOUR_REPO%2Fxbxsim.css

If you keep it in a subfolder, include that subfolder in the CSS URL.

## OBS

Add the finished Gamepad Viewer URL as an OBS Browser Source.
A starting browser-source size around 750 x 630 matches the native skin canvas.
You can resize the OBS source after confirming input alignment.

## Important

This is the first functional build made from the supplied artwork and the
current public Gamepad Viewer Xbox geometry. Test it with your controller.
If any artwork edge/hole is a few pixels off in the live page, send a screenshot
of this build running in Gamepad Viewer and the transform can be corrected precisely.
