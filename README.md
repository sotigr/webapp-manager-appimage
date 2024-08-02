Linux mint webapp manager AppImage builder

This repo uses a tool from simoniz0r called deb2appimage [https://github.com/simoniz0r/deb2appimage](https://github.com/simoniz0r/deb2appimage) to convert the linux mint webapp-manager deb file to a portable appimage format.

```sh
# Build
chmod +x deb2appimage.appimage
./deb2appimage.appimage -j ./webapp-manager.json -o ./out
```