# Description
Simple C++ playground project with CMake.

# Build and Run

```bash
mkdir build
cd build
cmake ..
cmake --build .
./Playground
```

## CMake presets

To List available presets run:

```bash
cmake --list-presets
cmake --build --list-presets
```

For example, to build with Clang on macOS run:

```bash
cmake --preset debug-clang-macos
cmake --build --preset clang-macos
./build/debug-clang-macos/Playground
```
