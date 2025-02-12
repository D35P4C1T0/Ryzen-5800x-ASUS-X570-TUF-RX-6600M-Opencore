**README.md**  
# Hackintosh-AMD-Ryzen-5800X-RX6600M-X570-TUF  

**OpenCore 1.0.3 Configuration for AMD Ryzen 7 5800X, RX 6600M, and ASUS X570 TUF Gaming**  
*A stable macOS Sequoia build using OpCore-Simplify templates and iMac19,1 SMBIOS.*  

---

## **Hardware Specifications**  

- **CPU:** AMD Ryzen 7 5800X  
- **GPU:** AMD Radeon RX 6600M
- **Motherboard:** ASUS X570 TUF Gaming (Wi-Fi)  
- **RAM:** 16GB DDR4 3600MHz  
- **Storage:** SATA SSD (Windows dual-boot)  
- **OpenCore:** 1.0.3  
- **SMBIOS:** iMac19,1  

>Please don't use this config as-is. Provide your own serials generated with GenSMBIOS.

---


## **Features**  

✅ **Working**  
- **AMD RX 6600M GPU Acceleration** (Metal, OpenGL, Video Encoding)  
- **USB Ports** (Fully mapped via USBMap Tool)
- **Audio** 
- **Ethernet** 
- **iServices** (iMessage, FaceTime, iCloud)  
- **Sleep/Wake** 

⚠️ **Not Working / Quirks**  
- **DRM Content** (Apple TV+, Netflix in Safari) – Use Chromium browsers.  
- **Sidecar** (iPad connectivity issues – likely GPU-related).  

---

## **Prerequisites**  

1. **BIOS Settings** (ASUS X570 TUF Gaming):  
   - **Above 4G Decoding:** Enabled  
   - **CSM (Compatibility Support Module):** Disabled  
   - **Secure Boot:** Disabled  
   - **TPM:** Disabled  
   - **SATA Mode:** AHCI  

2. **Tools:**  
   - [OpCore-Simplify](https://github.com/lzhoang2801/OpCore-Simplify) (Base configs)  
   - [USBMap Tool](https://github.com/USBToolBox) (for USB port mapping on Windows)  
   - [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) (for generating iMac19,1 SMBIOS)  
   - [OpenCore Auxiliary Tools](https://github.com/ic005k/OCAuxiliaryTools) (config.plist editing)  

---

## **Contributing**  
Feel free to submit PRs for improvements or open Issues for bugs. Include:  
- `config.plist` snippets.  
- IORegistry dumps (for hardware debugging).  

---

## **Credits**  

- [OpCore-Simplify](https://github.com/lzhoang2801/OpCore-Simplify) for the AMD OpenCore base.  
- [Dortania Guide](https://dortania.github.io) for general Hackintosh principles.  
- The [AMD-OSX](https://forum.amd-osx.com) community for kernel patches.  

---

**Disclaimer:**  
This configuration is provided "as-is." Hackintoshing violates Apple’s EULA – use at your own risk.  

---  
**Happy Hackintoshing!** �  🖥️
