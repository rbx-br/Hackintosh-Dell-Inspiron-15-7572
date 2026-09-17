# Hackintosh Dell Inspiron 15 7572
### Generate your own SMBIOS, recommended MacBookPro16,4

![Dell Inspiron 15 7572](https://github.com/user-attachments/assets/990b6359-04f5-43b0-8c00-a2868cd09bba)

## Basic description:
Intel® Core™ i5-8250U - Kaby Lake R

16GB DDR4 2400MHz

Intel® Graphics UHD 620 - 4GB ***(For 2GB change DeviceProperties > Add > PciRoot(0x0)/Pci(0x2,0x0) > framebuffer-unifiedmem to 00000080 on config.plist)***

Nvidia® GeForce™ MX150 4GB - ***Disabled***

Intel® Wireless 8265 - *Replaced*

Realtek® RTL8111 Gigabit Ethernet

Sunrise Point-LP High Definition Audio Controller - based on Realtek ALC256 ***(need patch see below)***

## This EFI can boot
![11](https://github.com/user-attachments/assets/492bf142-3e84-4bb3-9ff2-e6d08679e6a7) ***macOS Big Sur 11.7.10***


![12](https://github.com/user-attachments/assets/8772e7c3-cf53-4849-9d5e-c489f8fd36ea) ***macOS Monterey 12.7.6***


![13](https://github.com/user-attachments/assets/8a7caf06-b55b-4b15-a7c1-3756526d2404) ***macOS Ventura 13.7.8***


![14](https://github.com/user-attachments/assets/c0764b86-eb06-48f9-8934-67c5ffa7d377) ***macOS Sonoma 14.8.9***


![15](https://github.com/user-attachments/assets/9974bfe2-522c-408a-b045-0a17b377eb8d) ***macOS Sequoia 15.8***


![26](https://github.com/user-attachments/assets/e3f20b34-c05a-4dd7-a460-5680296a1919) ***macOS Tahoe 26.7***


# ✅ Working

Intel® Graphics UHD 620 ***(Metal 3 Support)***

Sound ***(needs [RPCore](https://github.com/luchina-gabriel/RP-CORE/releases/tag/1.0.2) or [OCLP](https://github.com/dortania/OpenCore-Legacy-Patcher/releases/tag/2.5.0) to work on Tahoe)***

Keyboard

Touchpad ***(Recommended Force Touch disable in system settings)***

Webcam

SD Card reader

Screen brightness control 

Ethernet

HDMI

iServices

WiFi ***(Using [HeliPort App](https://github.com/OpenIntelWireless/HeliPort/releases/tag/v2.0.0-alpha))***

Bluetooth

# ❌ Not working

NVIDIA® GeForce™ MX150 ***(Disabled because it is incompatible with macOS)***
#
![Dell 7572 screen](https://github.com/user-attachments/assets/53c64697-49d2-4b1c-bb9d-97aaa1cb3795)

