# Mahapps.PasswordBind
Issue on password binding -> is always reset to "" on page navigation

here the log:

'App8.exe' (CoreCLR: clrhost): Loaded 'C:\Program Files\dotnet\shared\Microsoft.NETCore.App\3.1.11\System.Diagnostics.FileVersionInfo.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
PasswordChanged
SetIsUpdating >True<
SetPassword >t<
BackupPassword >t<
OnPasswordPropertyChanged
GetIsUpdating >True<
SetIsUpdating >False<

PasswordChanged
SetIsUpdating >True<
SetPassword >te<
BackupPassword >te<
OnPasswordPropertyChanged
GetIsUpdating >True<
SetIsUpdating >False<

PasswordChanged
SetIsUpdating >True<
SetPassword >tes<
BackupPassword >tes<
OnPasswordPropertyChanged
GetIsUpdating >True<
SetIsUpdating >False<

PasswordChanged
SetIsUpdating >True<
SetPassword >test<
BackupPassword >test<
OnPasswordPropertyChanged
GetIsUpdating >True<
SetIsUpdating >False<
-------------------------------------- here I navigate back to main page
PasswordChanged
SetIsUpdating >True<
SetPassword ><
BackupPassword ><
OnPasswordPropertyChanged
GetIsUpdating >True<
SetIsUpdating >False<
The program '[0xA988] App8.exe' has exited with code 0 (0x0).
