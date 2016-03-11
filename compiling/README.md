DEPENDENCIES
------------

- Affdex SDK 2.0 (32 bit)
	- Should be installed to "C:\\Program Files (x86)\\Affectiva"
- Affectiva SDK License
	- Should be placed in "C:\\Program Files (x86)\\Affectiva\\Affdex SDK\\affdex.license"
- OpenCV for Windows 2.4.9: http://sourceforge.net/projects/opencvlibrary/files/opencv-win/2.4.9/
- Visual Studio 2013 or higher (for editing and compiling the EXE)

COMPILING
---------

- Download OpenCV and place the folder in the root folder.
- Open the Microsoft Visual Studio project file and compile.
- This will output a ".exe" file in "Release/".

RUNNING
-------

- "opencv_ffmpeg248.dll" is a necessary codec for running video analysis.
	- It needs to be placed in the same directory as the executable.
- Open CMD and cd to the folder contain the ".exe" file.
- Run using "sdk_demo.exe [path to file]".
- Data points are outputted to STDOUT as JSON.

TROUBLESHOOTING
---------------

- If you cannot compile, make sure OpenCV is in the root folder.
- If you cannot run the executable, make sure you have an SDK license in the appropriate folder (where the SDK is located).
