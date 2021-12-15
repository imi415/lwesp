# How to build examples

Make sure gcc and cmake is installed, refer to your distro documentation.

```bash
mkdir build && cd build
cmake ..
make -jN # N=CPU number
```

After that you will find executables under the build directory.
