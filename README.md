# i3 10100F High Sierra Hackintosh
Comet Lake + NVIDIA based OpenCore EFI for you folks.
I've digged out of how i can SPOOF a CPU on OpenCore and found it out. I made this OpenCore EFI for one of my user. You guys can test it with your Comet Lake CPU(i5/i7).
- EFI contains IntelMausi.kext for ethernet, if you have another card e.g RTL81xx, you should add the kext OC/Kexts and plist.
- OpenCore 0.7.6
- Used iMac18,3 SMBIOS with shikivga=40 boot-arg
- Some of the kexts might be a little bit outdated, check that on post-install w/ Hackintool.
- Special note for Codec: my boy couldn't work the sound even he tried every layout-id, so he used VoodooHDA instead of AppleALC and he has sound now.

# Tested system specs
Hardware  | Model
------------- | -------------
CPU  | Intel Core i3-10100F
GPU | NVIDIA GT 1030
MOBO  | MSI H410M PRO-VH
RAM  | 8GB
Storage  | 500GB HDD + 240GB SSD
Codec  | Realtek® ALC892/ALC897 Codec
Ethernet  | Intel® I219V Gigabit LAN controller

![](https://www.technopat.net/sosyal/eklenti/i3-10100f_highsierra_opencore-png.1255589/)
