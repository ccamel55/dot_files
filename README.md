# dot_files

Collection of config files for Linux and Mac OS

**Note: This assumes you use ZSH as default shell*

## Linux Stuff

Confirmed to work on the following specs

- Distro: `Fedora 40`
- CPU: `Ryzen 9 7950x3d`
- Motherboard: `Asus ProArt x670E`
- Memory: `Corsair Vengence 2x32Gb 5600 CL-40`
- SSD (OS drive): `Samsung 990 Pro 4Tb`
- GPU: `EVGA RTX 3090 FTW3`

### Useful stuff

- https://github.com/devangshekhawat/Fedora-40-Post-Install-Guide/blob/main/README.md
- https://github.com/paulmcauley/klassy
- https://rpmfusion.org/Howto/NVIDIA
- https://github.com/vinceliuice/McMojave-cursors
- https://dlvhdr.github.io/gh-dash/ 
- https://docs.astronvim.com/

### Regenerate akmods

- `akmods --force`
- `dracut -f --regenerate-all`

### AMD iGPU passthrough

- https://github.com/isc30/ryzen-gpu-passthrough-proxmox
- https://www.reddit.com/r/VFIO/comments/16mrk6j/amd_7000_seriesraphaelrdna2_igpu_passthrough/
- https://ostechnix.com/enable-uefi-support-for-kvm-virtual-machines-in-linux/
- https://www.reddit.com/r/VFIO/comments/yyqz5j/cant_find_the_rom_file/
- https://passthroughpo.st/using-evdev-passthrough-seamless-vm-input/
