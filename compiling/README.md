DEPENDENCIES
------------

- Affdex SDK 2.0 (32 bit)
- OpenCV for Windows 2.4.9: http://sourceforge.net/projects/opencvlibrary/files/opencv-win/2.4.9/
- Visual Studio 2013 or higher
- Affectiva SDK License

Data points are outputted to STDOUT as JSON.

COMPILING
---------

- Download OpenCV and place the folder in the root folder.
- Open the "opencv-webcam-demo/opencv-webcam-demo" file and use Visual Studio to compile.
- This will output a ".exe" file in "Release/".
- "opencv_ffmpeg248.dll" is a necessary codec for running video analysis.
	- It needs to be placed in the same directory as the executable.


RUNNING
-------

- Open CMD and cd to the folder contain the ".exe" file.
- Run using "sdk_demo.exe [path to file]"
	- Type options: video

TROUBLESHOOTING
---------------

- If you cannot compile, make sure OpenCV is in the root folder
- If you cannot run the executable, make sure you have an SDK license in the appropriate folder (where the SDK is located).