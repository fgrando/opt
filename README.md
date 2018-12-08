# opt
my basic settings for windows installations (apps and other goods)


# Installation
Checkout this repo in C:\opt. For example, the expected path of this file is C:\opt\README.md.
If you want to use a different folder, maybe other configurations will have to change as well.

The following commands need elevation (run cmd as administrator).

Update system PATH variable:
SETX PATH "%PATH%;C:\opt\apps"

Add the special cmd to system32 (this load the aliases and any other config we need)
xcopy C:\opt\apps\sources\cmd\cmdd.bat %windir%\system32\cmdd.bat