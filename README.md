# slay
Darkplaces-based Quake 1 engine and tools

Mac and Windows supported right now.
* Mac requires a recent version of Xcode.  Tested currently on 10.15.  Currently the drawing is incorrect.
* Windows has been tested with MSVC 2017.

To build:

* Check out the repo with submodules:
```
git clone --recurse-submodules https://github.com/kattkieru/slay.git
```

* Do the CMake dance
```
mkdir build
cd build
cmake -G "Xcode" ..
cmake --build .
```

Or if you like, build using Xcode.

* Copy the resulting executable into the proper directory and launch from the terminal.

