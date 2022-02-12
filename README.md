# rawdrawandroid-for-Windows
Previously, I could not build it on windows, but now I have done it easily and simply

# What's it?  
This is a copy of the repository: https://github.com/cnlohr/rawdrawandroid  
I mainly touched on the Makefile, I had to fix and change something there to build the application on Windows  
  
# How to build it?

1. You must have installed:  
- **Android SDK (android-29 / 30 / 31, to choose from)**  
- **Build-tools (i installed 31.0.0)**  
- **NDK (i installed 23.0.7599858, it can be newer)**  
- **7-zip**  
- **you should install gnuwin32 3.81 (and newer)**  
____
Review the Makefile and change the relative paths to your folders. You may also have to change the path to 7-zip  
Нou may also need to recreate the signature file.  
For build apk start Command Line Windows (cmd.exe)  
Use "cd" and navigate to the path to your project  
Use the command "path to GNUmake", I had it like this: "C:\Program Files (x86)\GnuWin32\bin\make.exe"  
Then the process of compiling and assembling the project will go on  
  
# Thanks
CnLohr <3
