# Lite-Debian
Build debian with kde-plasma (minimum), nvidia-amd-intel graphics, and xorg

*Install in Debian/Ubuntu*
`sudo apt-get install live-build`
`sudo lb config -d bullseye --debian-installer live --debian-installer-distribution bullseye --debian-installer-gui true --archive-areas "main contrib non-free" --debootstrap-options "--variant=minbase"`
`sudo lb build`

*Rebild in Debian/Ubuntu*
`sudo lb clean`
`sudo lb config -d bullseye --debian-installer live --debian-installer-distribution bullseye --debian-installer-gui true --archive-areas "main contrib non-free" --debootstrap-options "--variant=minbase"`
`sudo lb build`
