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

### Fix audio

- restart audio `alsactl init`
- restart pipewire `systemctl restart --user pipewire`

~- disable auto suspend USB with udev rules and grub kernel CMD `usbcore.autosuspend=-1`~
- disable amd iommu (add to kernel parameters) `amd_iommu=off`
- update pipewire config `/usr/share/pipewire/pipewire.conf` and copy to `~/.config/pipewire/`


```
        default.clock.quantum     = 2048
        default.clock.min-quantum = 1024
        default.clock.max-quantum = 4096

```

