A multi-platform application that displays UTC time.  Useful for ham radio operators.

![image](https://github.com/user-attachments/assets/d4a562c7-db33-48be-b0fb-3e0aa940483e)

NOTE: I do not have access to all operating systems and machine types.  Given the complexities of writing a single app for multiple operating systems, I cannot guarantee that every item of text or button in the app is displayed optimally.  This application has been tested on the following computers.

Recent Apple Intel and Apple Silicon (ARM) computers.

Virtualized Windows 10 & 11.

Virtualized Linux.


Note: To install on a Raspberry Pi - Select the Linux Arm32 or Linux Arm64 version as appropriate.  

	* You will need to install the libunwind8 library on your Pi in order to run NixieClock. You can install the library from Terminal with this command:

		sudo apt-get install libunwind8	
		
	* NixieClock will not run on the original Raspberry Pi or the Raspberry Pi Zero which have the older ARMv6.  

	* NixieClock may run on similar "single-board" computers using the ARMv7 or later CPU.  Your milage may vary.



Note: NixieClock has a convenient Tool Bar with helpful icons that are used to set preferences.  

	The NixieClock window always floats on top of all other application windows.  If you elect to hide the Tool Bar, you will need to access the preference settings via the NixieClock menu bar.  Depending upon your machine and operating system, the menu bar may not be immediately visible.  This is because even though the NixieClock window is always on top; the NixieClock app may not be the top most open application.  You may need to cycle through your open applications to find the NixieClock menu bar.  I am still working to have NixieClock play well with multiple monitors.  
