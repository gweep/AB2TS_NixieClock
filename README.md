A multi-platform application that displays UTC time.  Useful for ham radio operators.

![image](https://github.com/gweep/AB2TS_NixieClock/blob/main/ScreenShots/Large_With_Date.tiff)


![image](https://github.com/gweep/AB2TS_NixieClock/blob/main/ScreenShots/Small_No_Date.tiff)



NOTE: I do not have access to all operating systems and machine types.  Given the complexities of writing a single app for multiple operating systems, I cannot guarantee that every item of text or button in the app is displayed optimally.  This application has been tested on the following computers:

* Recent 64 bit Apple Intel and Apple Silicon (ARM) computers; MacOS 10.14 and higher.
* Virtualized Windows 10 & 11; 64 bit Intel and ARM.
* Virtualized Linux; 32 & 64 bit Intel and 64 bit ARM.

Extract the zip file in-place.  Do not change the folder names, the relative directory structure needs to remain intact.  On Linux machines you may have to designate the application as executable in the application's preference/info window.  Depending upon how you extract the zip file; the program may be buried in an extra layer of folders.  It seems to be OK to move the inner most folder up a layer and delete the superfluous empty folder.  

Note: To install on a Raspberry Pi - Select the Linux Arm32 or Linux Arm64 version as appropriate.

You will need to install the libunwind8 library on your Pi in order to run NixieClock. You can install the library from Terminal with this command:

    sudo apt-get install libunwind8

* NixieClock will not run on the original Raspberry Pi or the Raspberry Pi Zero which have the older ARMv6.  
* NixieClock may run on similar "single-board" computers using the ARMv7 or later CPU.  Your milage may vary.

Note: NixieClock has a convenient Tool Bar with helpful icons that are used to set preferences.

The NixieClock window always floats on top of all other application windows.  If you elect to hide the Tool Bar, you will need to access the preference settings via the NixieClock menu bar.  Depending upon your machine and operating system, the menu bar may not be immediately visible.  This is because even though the NixieClock window is always on top; the NixieClock app may not be the top most open application.  You may need to cycle through your open applications to find the NixieClock menu bar.  I am still working to have NixieClock play well with multiple monitors.  
