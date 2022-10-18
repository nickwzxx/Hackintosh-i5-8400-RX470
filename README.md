# OpenCore Hackintosh for i5-8400 and RX470

![About Mac Screenshot](https://user-images.githubusercontent.com/116093195/196463999-4ea362f4-5e7a-4072-bc9e-bbc5de8f06b9.png)

**Hi everyone! I wan't to share my personal EFI folder for Hackintosh.**

## My hardware configuration:
- CPU: Intel Core i5 8400
- GPU: MSI RX470 Armor OC 4GB
- Motherboard: ASUS Prime H310M-K R2.0
- Network Controller: Realtek RTL8111H
- Chipset: H310
- Audio Codec: Realtek ALC887 8-Channel
- RAM: Goodram IRDM X 16GB 2666MHz DDR4
- SSD: Kingston 120GB (SA400S37120G)
- HDD: Toshiba 1TB (HDWD110)
- DVD: ASUS (DRW-24D5MT)

## Note
**It is not a tutorial. The steps and things to do are not mentioned. Please read the official Dortania's guide.**

**This is my personal home project. I have no responsibility for any damage caused by the release of this project.**

## About Hackintosh:
- Works on macOS Big Sur, Monterey and Ventura (Beta 11)
- It's a release version of OpenCore 0.8.5.
- Any debug thing is disabled, only OpenCore bootloader with GUI and Apple Logo

### Works:
- All iServices
- FileVault
- All types of DRM
- OpenCore GUI

### Doesn't work:
- Everything works fine (I think)

### I didn't test:
- DisplayPort output
- macOS Updates

## Do not forget!
- **Do not forget to generate iMacPro1,1 SMBIOS with GenSMBIOS and insert it to config through ProperTree**
- **Do not forget to map your USB with USBToolBox and put your UTBMap kext into Kexts folder (There is already USBToolBox kext)**
- **Do not forget to make your own SSDT's with SSDTTime and put them into ACPI folder (I put prebuilt ones and if you are too lazy you can skip this)**

## Gallery
![Screenshot 1](https://user-images.githubusercontent.com/116093195/196487794-c5f11050-51c5-41fa-a2ff-a9768b7f00a0.png)
![Screenshot 2](https://user-images.githubusercontent.com/116093195/196487847-6661e31e-78ea-4b79-b21e-50db392af58f.png)

