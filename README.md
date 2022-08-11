# Minimal example of a CLAP plugin

Does nothing but the CLAP way :-)

## Building the plugin

```shell
git clone https://github.com/git-moss/clap-tutorials.git
cd clap-saw-demo
git submodule update --init --recursive
cmake -Bbuild -DCMAKE_BUILD_TYPE=Debug
cmake --build build --config Debug
```

The result CLAP file will be in `ignore/build/clap-saw-demo.clap`.