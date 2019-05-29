This is a fork of Worleydl hdr-switcher.

Updated it to be able to compile with VisualStudio 2019. 

To compile it you need to:
Disable precompiled header, set to NO. 
and
Add nvapi64.lib to your project. Go to Project propreties > Linker > input and write ;nvapi64.lib;


Original README:
This application attempts to enable HDR rendering on compatible devices connected to a Nvidia GPU.

The screen will go black for 5 seconds while the application attempts to enable HDR mode.  HDR mode will stay enabled until you close the application or press enter.

While enabled it's possible to run other applications like emulators with special tone mapper shaders to take advantage of HDR without modifying the underlying code inside the application.
