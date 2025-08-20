# toolchains
CMake toolchain files

Command line:
```
cmake -G "Visual Studio 17 2022" -A x64 -B bin64 -DCMAKE_TOOLCHAIN_FILE=C:/vcpkg/scripts/buildsystems/vcpkg.cmake -DVCPKG_CHAINLOAD_TOOLCHAIN_FILE="C:/Users/vinnie/src/toolchains/msvc.cmake"
```
