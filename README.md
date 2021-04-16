# Arch Linux on Ideapad-l340 gaming
Things needed to have after install of Arch Linux on Ideapad L340 Gaming (other L340 have similar specs so you can use some drivers))

# what works
- WiFi
- GPU acceleration
- Ethernet (works out of the box)
- Webcam (out of the box)
- Touchpad (out of the box)
- Sound (out of the box)
- microphone (out of the box)

# what doesn't work
- Bluetooth
- *Wayland partially*

# How to Install

- WiFi driver:
install this package "rtl8821ce-dkms-git-1.0.5.r80.g08060c5-1-x86_64.pkg.tar.xz"
**you need to be connected to the internet first for installing this package** *i recommend using USB hotspot on a phone or finding ethernet cable*


- NVida GeForce driver
if you haven't installed it in Arch installation process:

1. go to
https://www.nvidia.com/Download/index.aspx?lang=en-us


2. pick your GTX card details (notebook) and download .run file.


3.```sudo chmod +x ./NVIDIA-Linux-x86_64(version etc.)


./NVIDIA-Linux-x86_64(version etc.)```
