xwa_hook_time

This hook reduces the CPU usage. The side effect is that the framerate is reduced.

For more informations, please see the following thread at xwaupgrade.com:
http://www.xwaupgrade.com/phpBB3008/viewtopic.php?f=10&t=11338


*** Requirements ***

This dll requires:
- Windows XP SP2 or superior
- xwa_hook_main


*** Setup ***

1) add hook_time.dll to dinput_hooks.lst

2) place hook_time.dll next to xwingalliance.exe

3) edit xwingalliance.exe:

You can manually apply the modifications with an hexadecimal editor, or you can use XwaExePatcher to have a GUI.

# To call the hook that reduces CPU usage
At offset 10D810, replace E82BF8FFFF8B with E81BA70900C3.
At offset 10D830, replace E80BF8FFFF8B with E8FBA60900C3.


*** Credits ***

- Jérémy Ansel (JeremyaFr)
