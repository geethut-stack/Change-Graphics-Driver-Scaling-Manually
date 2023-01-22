#Specified path:


HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\GraphicsDrivers\Configuration\%display Key%\00\00\

"Scaling"=dword:3


There must be multi %display Key% exist, you should find out the one you are using. This is easy, you can delete all keys first, and then change your current monitor's setting. There will be a new key automatically created and that's your display. Below is the scaling value options:

2: Center Image

3: Full Screen should be set

4: Maitain Aspect Ratio

