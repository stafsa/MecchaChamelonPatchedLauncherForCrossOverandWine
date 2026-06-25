# MecchaChameleonPatchedLauncherForCrossOverandWine
I patched Meccha Chameleon's launcher to stop checking whether VC++ is installed or not, for users running it on CrossOver and Wine to be able to play



Meccha Chameleon's launcher(PenguinHotel.exe) checks whether VC is installed or not using LoadLibraryW, registry checks and path checks.This patch basically disables those checks and continue the normal behaviour of the launcher.No function was affected from this patch other than FUN_140001000.The patched executeable can be installed from the releases part.
# Tags
Meccha Chameleon Mac, 
VC++ Meccha Chameleon, 
Meccha Chameleon CrossOver, 
