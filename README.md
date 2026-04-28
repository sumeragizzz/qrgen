# qrgen

## Build commands

```bash
cd qrgen/
cmake --preset "GCC 15.2.0 x86_64-w64-mingw32 (ucrt64)"
cmake --build --preset "GCC 15.2.0 x86_64-w64-mingw32 (ucrt64)"
```

## Required libraries

- OpenCV
- CLI11 (downloaded automatically via `FetchContent` in `CMakeLists.txt`)

## Run

```bash
./out/build/GCC 15.2.0 x86_64-w64-mingw32 (ucrt64)/qrgen
```
