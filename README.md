# Build-Scheme-for-Sublime-Text-3-MacOS

Hello! 

This is a custom build scheme for sublime text 3 to get input / output alongside the code.

1. C++11 build file uses g++-9 and compiles on standards of C++11.
2. GNU++14 build file uses g++-9 and compiles on standards of GNU++14.

Steps to create your own build file : 

1. Go to Sublime Text 3 -> Tools -> Build System -> New Build System
2. A new file will open, named, untitled.sublime-build
3. Copy paste either the C++11 or GNU++14 contents into the file
4. Save the file as, fileName.sublime-build, in the location shown decided by the sublime. (DO NOT CHANGE THE LOCATION)
5. Go to Tools -> Build System -> Select the build system (by the name you selected)
