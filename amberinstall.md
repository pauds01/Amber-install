# AmberTools installation

### First of all you have to install cmake
```
wget -nc https://github.com/Kitware/CMake/releases/download/v3.29.0-rc1/cmake-3.29.0-rc1.tar.gz

tar zxvf cmake-3.29.0-rc1.tar.gz
cd cmake-3.29.0-rc1
./configure
gmake
sudo make install

```

#### Once you have cmake, you go to the Amber page and download both tar files. When you have them downloaded, I suggest to create a new folder at home called software for example and move there the tar files. Then:

```

bunzip2 Amber*
tar xvf AmberTools23.tar
tar xvf Amber22.tar
cd amber22_src/build
./run_cmake

```

