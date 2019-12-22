# Headless installation

1. Burn image to SD card
2. Create an empty file called "ssh" on the boot device
3. Copy the [wpa_supplicant.conf](wpa_supplicant.conf) file to the boot device and edit with the correct Wifi settings
4. Start pi and find IP address (using router or by name raspberrypi.local)
5. SSH details:
    - user: pi
    - password: raspberry
