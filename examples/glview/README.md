Simple OpenGL viewer for glTF geometry.

## Requirements

* premake4 : Requires recent `premake4` for macosx and linux, `premake5` for windows.
* GLEW
  * Ubuntu 16.04: sudo apt install libglew-dev
* glfw3
  * Ubuntu 16.04: sudo apt install libglfw3-dev

### MacOSX and Linux


    # optional. set pkg-config path to find glfw3
    $ export PKG_CONFIG_PATH=/path/to/pkgconfig

    > premake4 gmake
    $ make

### Windows(not tested well)

Edit glew and glfw path in `premake4.lua`, then

    > premake5.exe vs2013

Open .sln in Visual Studio 2013

When running .exe, glew and glfw dll must exist in the working directory.

## TODO

* [ ] PBR Material
  * [ ] PBR Texture.
* [ ] Animation
