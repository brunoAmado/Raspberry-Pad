
lohriialo commented May 29, 2024

Incase anyone else is facing similar issues with pios 64bit bookworm, here's what works for me

step 1.

sudo wget https://datasheets.raspberrypi.com/cmio/dt-blob-disp1-cam1.bin -O /boot/dt-blob.bin

sudo reboot

steps 2.

sudo wget https://datasheets.raspberrypi.com/cmio/dt-blob-disp1-only.bin -O /boot/firmware/dt-blob.bin

sudo reboot
