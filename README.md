# Minimal example of a CLAP plugin

Does nothing but the CLAP way :-)

## Building the plugin

```shell
git clone https://github.com/git-moss/clap-tutorials.git
cd clap-tutorials
git submodule update --init --recursive
cmake -Bbuild -DCMAKE_BUILD_TYPE=Debug
cmake --build build --config Debug
```

The result CLAP file will be in the build folder. E.g. on Windows in `build/Debug/moss-clap.clap`.
