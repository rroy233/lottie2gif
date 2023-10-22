## lottie2gif

A plugin used by [StickerDownloader](https://github.com/rroy233/StickerDownloader) to convert .tgs sticker into .gif file.
Based on [rlottie](https://github.com/Samsung/rlottie).

### Requirement

- cmake 3.3+
- build-tools for c++ (linitke g++,Visual Studio)

### Clone Project

```shell
git clone --recursive https://github.com/rroy233/lottie2gif.git
```

### Build (Linux)


```shell
# create build folder
mkdir build
cd build/

# use cmake to create makefile
cmake ..

# build
make

# move executive to StickerDownloader
cd ..
mv output/lottie2gif path/to/StickerDownloader/lottie2gif/lottie2gif
```

### Build (Windows)

```shell
# create build folder
mkdir build
cd build

# use cmake to create makefile
cmake ..
```

You can open `lottie2gif.sln` file using Visual Studio to build.

Find `lottie2gif.exe` and `rlottie.dll`, then move them into `StickerDownloader/lottie2gif/` folder.

