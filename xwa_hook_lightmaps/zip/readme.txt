﻿xwa_hook_lightmaps

This hook replaces a static buffer with a dynamic one in lightmaps loading.


*** Requirements ***

This dll requires:
- Windows XP SP2 or superior
- xwa_hook_main


*** Setup ***

1) add hook_lightmaps.dll to dinput_hooks.lst

2) place hook_lightmaps.dll next to xwingalliance.exe

3) edit xwingalliance.exe:

You can manually apply the modifications with an hexadecimal editor, or you can use XwaExePatcher to have a GUI.

# To call the hook that creates lightmaps
At offset 040F60, replace 8D8BB0D164003BC2895424347E4B with 505356E8C86F160083C40C90EB4B.
At offset 040FCD, replace 8D83B0D16400 with 909090909090.


*** Credits ***

- Jérémy Ansel (JeremyaFr)
