### ripple-libpp
---
https://github.com/ripple/ripple-libpp

```cc
```

```sh
git clone --recursive <location>
git submodule init
git submodule update

cd $(YOUR_RIPPLE_LIBPP_DIRECTORY)
mkdir -p build/debug
cd build/debug
cmake ../.. -DCMAKE_BUILD_TYPE=Debug
cmake --build .
./ripplelibppdemo

cd %YOUR_RIPPLE_LIBPP_DIRECTORY%
mkdir build
cd build
cd build
cmake -G"Visual Studio 15 2019 Win64" ..
cmake --build .
.\Debug\ripplelibppdemo.exe

```

```
```


