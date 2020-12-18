# macOS-10.15.5-OpenCore-z370
 My working EFI for my MSI z370 SLI Gaming Plus rig

Specs:
* MSI z370 Gaming SLI Plus 
* i7-8700k
* Sapphire Nitro+ 8GB
* 16GB DDR4 GSkill Ram
* 2 x SSDs 3D SATA

I have a Fenvi T919 Wireless card as well as ethernet. The card works OOB with Big Sur but seems to work "better" with [this kext](https://github.com/acidanthera/AirportBrcmFixup)

USB C seems to work fairly well too!

Premise of hack came from this guide: https://dortania.github.io/OpenCore-Desktop-Guide/

iServices activated with: https://dortania.github.io/OpenCore-Desktop-Guide/post-install/iservices.html

I am running a dualboot across 2 different SSD's with Win 10 and Catalina. Win 10 seems to boot fine from OpenCore menu. Do your best to keep their respeictve EFI seperate (ie Catalina's on its own SSD and Win 10's EFI on its own SSD).
