xwa_hook_backdrops

This hook adds starfield backdrops to skirmish mission.


*** Requirements ***

This dll requires:
- Windows XP SP2 or superior
- xwa_hook_main


*** Setup ***

1) add hook_backdrops.dll to dinput_hooks.lst

2) place hook_backdrops.dll next to xwingalliance.exe

3) edit xwingalliance.exe:

You can manually apply the modifications with an hexadecimal editor, or you can use XwaExePatcher to have a GUI.

# To call the hook that adds starfield backdrops
At offset 17A3D9, replace 33DB85C08944241C0F8E4D0300008B74241469F63E0E0000 with 8D5C24145350E83CDB020083C408E9480300009090909090.


*** Credits ***

- Jérémy Ansel (JeremyaFr)
