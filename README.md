# Unofficial TWRP for Samsung Galaxy Tab Pro 8.4 (SM-T320)

This is an **unofficial build of TWRP (Team Win Recovery Project)** for the **Samsung Galaxy Tab Pro 8.4 (Wi-Fi, model SM-T320)**.  
It was tested and confirmed working on LineageOS 18.1 and Android 11-based ROMs.


## Disclaimer
This recovery is **unofficial** and provided as-is.  
I am not responsible for any damage, data loss, or boot issues that may occur.  
Flash it at your own risk.


## What does "FOTA" mean?

**FOTA** stands for *Firmware Over-The-Air*. 
It's a tool used to install Android software updates from recovery, official TWRP doesn't include FOTA.


## Flashing Instructions (Using Odin)

1. Download Odin [here](https://samsungodin.com/download/Odin3_v3.12.3.zip). and install Samsung USB drivers.
2. **Power off your tablet**.
3. Boot into **Download Mode**:
   - Hold **Power + Volume Down + Home** until you see the warning screen.
   - Press **Volume Up** to continue.
4. Open **Odin** on your PC.
5. Connect your tablet with a USB cable.
6. In Odin:
   - Click the **AP** button and select your TWRP `.img` file.
   - Go to **Options** tab and make sure **Auto Reboot** is **unchecked**.
7. Click **Start** and wait until it says **PASS**.
8. When done, **manually boot into recovery**:
   - Hold **Power + Volume Up + Home** immediately after flashing.
9. TWRP should appear!

## Credits
- **Team Win Recovery Project (TWRP)**
- **LineageOS Community**
- Device testing by **@CreeperGuy0842**

---

**Enjoy!**
If this helped you, consider giving the repo a ⭐ on GitHub!
