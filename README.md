![SDesk-ProjectBanner](https://github.com/SteveStudios/SDesk/assets/90519370/bdc49397-1d40-4e47-8114-5116fc8aafdf)

# This is the repository for the SDesk WSL root filesystem.

## Building
### Prequisites
- Arch Linux, SDesk, or another Arch-Derived Distribution
- The [archiso](https://archlinux.org/packages/extra/any/archiso/) package
- OPTIONAL (But recommended): The [qemu-full](https://archlinux.org/packages/extra/x86_64/qemu-full/) package for testing the disk image
  
### Compiling the Disk Image for the first time
Run the following command to build the SDesk disk image:

```
sudo ./build.sh
```

### Recompiling the Disk Image
Run the following commands to rebuild the SDesk disk image:

```
sudo rm -rf ./work
sudo rm -rf ./out
sudo ./build.sh
```
[Archiso man page](https://wiki.archlinux.org/title/archiso)
