# toolchains
CMake toolchain files

Command lines:

Visual Studio 2026
```
cmake -G "Visual Studio 18 2026" -A x64 -B bin64 -DBUILD_TESTING=ON -DCMAKE_TOOLCHAIN_FILE=C:/vcpkg/scripts/buildsystems/vcpkg.cmake -DVCPKG_CHAINLOAD_TOOLCHAIN_FILE="C:/Users/vinnie/src/toolchains/msvc.cmake"
```

Visual Studio 2022
```
cmake -G "Visual Studio 17 2022" -A x64 -B bin64 -DBUILD_TESTING=ON -DCMAKE_TOOLCHAIN_FILE=C:/vcpkg/scripts/buildsystems/vcpkg.cmake -DVCPKG_CHAINLOAD_TOOLCHAIN_FILE="C:/Users/vinnie/src/toolchains/msvc.cmake"
```
