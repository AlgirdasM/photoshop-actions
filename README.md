# Photostop actions

These are my Photoshop Actions that I frequently use on my assigments.

## Install actions
1. Clone or Download repository
2. Open Adobe Photoshop
3. Window - check Actions option to open up Actions sidebar
4. Press on hamgurger icon
5. Load Actions...
6. Locate AM_actions.atn file and load it

You shoud see AM actions folder in Actions sidebar

*I'm using Adobe Photoshop CC 2018. I didn't test it with other versions of Photoshop.*

## Resize for web(1200x800px)
Default action for web sized images.
* Flatten image
* Convert to sRGB
* Change resolution to 72 DPI
* Fit image to 1200(width) 800(heigth)px
* Sharpen a bit
* Save as image

### Batch process on Mac OS X and Adobe Photoshop CC 2018

1. Open Adobe Photoshop, then File -> Automate -> Batch...
2. Setup:
**Play**
Set: AM actions
Action: Resize for web(1200x800px)
3. Select source Folder
4. Select destination as Folder
5. Check Override Action "Save As" Commands
6. Press ok

*I usually adjust File Naming options to add web keyword in the end of filename separated by _ .*