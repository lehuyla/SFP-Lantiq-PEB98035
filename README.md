# SFP-Lantiq-PEB98035 (G010SP-MA5671A or same)
Developed based on the "LuCI openwrt-19.07 branch git-22.099.58928-786ebc9-0807-v1.15-WiFiX" firmware version, with added display content and customizations. 
Check cat /proc/mtd and mtd -e image1 write /tmp/mtd2_linux.bin image1 and mtd -e linux write /tmp/mtd2_linux.bin linux. 
Make direct edits on the SFP using the `sync` command, and use `dd if=/dev/mtd2 of=/tmp/mtd2_linux.bin` to create a backup copy.

