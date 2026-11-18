# Wipe Compare — Quick A/B Image Wipe Viewer

> **Note:** This repository serves as a visual and technical showcase of a custom desktop utility. Source code and binaries are kept private.

![Wipe Compare Demo](wipe_compare_demo.gif)
![Wipe Compare Demo](wipe_compare_demo_linkedin.gif)

SETUP (once)
1. Unzip this folder somewhere permanent, e.g.  C:\Tools\WipeCompare
   (keep the three files together).
2. Right-click "Wipe Compare.bat" > Show more options > Send to > Desktop (create shortcut).
3. Optional, for the nice icon: right-click the new desktop shortcut > Properties >
   Change Icon... > Browse > pick wipe_compare.ico in this folder > OK.
4. Needs Python on Windows. The first launch installs Pillow automatically
   (a black window may appear for a few seconds that one time).
   
USE
- Select two images in Explorer and drag them onto the desktop icon.
- Or double-click the icon: it asks for the FIRST (left) and then the SECOND (right) image.
- If the sides come out the wrong way round, just press S.

## Keyboard & Mouse Controls

| Input | Action |
| :--- | :--- |
| **Left-Drag** | Move the A/B wipe divider |
| **Double-Click / `C`** | Center the divider |
| **Scroll Wheel / `+` `-`** | Zoom in/out around the cursor |
| **Middle-Drag / `Space` + Drag** | Pan across the canvas |
| **`Left` / `Right` Arrows** | Nudge divider (`Shift` for larger steps) |
| **`S`** | Swap Left (A) and Right (B) images |
| **`G` / `H`** | Toggle grab handle or hide divider/labels |
| **`F` / `1` / `F11`** | Fit to window / 100% actual pixels / Fullscreen |

The current zoom % is shown in the window title.

##NOTES
- Different resolutions are fine: both images are fitted to the window,
  so a 1376x768 and a 2560x1440 version line up.
- Reads PNG, JPG, TIFF (8 and 16 bit), BMP, WEBP, TGA, GIF. Not EXR.
- Display is plain sRGB, no color management or LUT.
