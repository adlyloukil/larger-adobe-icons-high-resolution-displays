# How to make Adobe Photoshop's Icons larger on higher resolution (DPI) displays

## Guide

1. Search "run" or type windows key +r
2. type regedit and hit enter
3. Click Machine -> Software -> Microsoft -> Windows -> CurrentVersion -> SideBySide
4. Right Click New DWORD 32bit value PreferExternalManifest
5. Right Click "modify" change value from 0 to 1 and click decimal and press ok and close
6. Put the manifest file ( found in this respository) into the Adobe photoshop folder near the .exe

### Reference:

https://www.danantonielli.com/adobe-app-scaling-on-high-dpi-displays-fix
