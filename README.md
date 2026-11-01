# NXS-Boot-Stick
NXS-Boot-Stick is a small tool for booting NixOS (daily) installation media directly from iso file. Just drag&drop iso file onto NXS-Boot-Stick and after reboot a small menu shows up for further action.
# Features
- NixOS graphical & minimal are bootable (uefi-only)
- Supported ISOs: All NixOS Live Media of 26.05 series
- Provide boot menu
# Usage
It was build by using tools which are available on every NixOS installation media. I provide an img file for writing to usb/ssd device. I am using 'Gnome-Disk-Utility' for that, there are a lot of tools like Rufus, Ethcher, KDE ISO Image Writer, dd etc. After burning it to your device, you just need to extend second disk partiton with Gparted.

1. Get 'NXS-Boot-Stick.gz' release and decompress it.
2. Write it to usb/ssd device (min. of 8GB recommended)
3. Resize second partition with Gparted. Open Gparted, choose 'Resize' option and extend partition. Both partitions are fat32 and this version only works on fat32.
4. Now put NixOS iso files to 'ISOs' directory on second partition and reboot.
# Screenshots
<img width="830" height="540" alt="grub-emu_NXS-boot-menu1_cut" src="https://github.com/user-attachments/assets/9b939700-ffcb-41de-ab15-a89d644bb768" />
<img width="830" height="600" alt="grub-emu_NXS-boot-menu3_cut" src="https://github.com/user-attachments/assets/199a0ed4-4305-4c20-a55f-3ca2f04e1426" />
<img width="830" height="600" alt="nixos-boot-menu" src="https://github.com/user-attachments/assets/b46fd84a-8c6d-4dd1-9e2e-98bb26f010ce" />




