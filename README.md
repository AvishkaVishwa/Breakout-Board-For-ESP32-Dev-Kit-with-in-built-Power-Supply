# ESP32 & ESP32-S3 Breakout Boards with Onboard Power Supply

This repository contains the KiCad 9 design files designed for the **ESP32 DevKit** and **ESP32-S3 DevKit**.  The boards include an **integrated power supply** based on the **LM2596S-5.0** buck converter, allowing direct 12V input to be regulated down to 5V for powering the ESP32 modules and peripherals.

---

## 📷 Hardware Preview
### ESP32 Breakout Board

<p align="center">
  <img src="Assests\photo_2025-09-28_22-46-33.jpg" width="620"/>
</p>


### ESP32-S3 Breakout Board

<p align="center">
  <img src="Assests\photo_2025-09-28_22-46-28.jpg" width="620"/>
</p>

---

## ✨ Features
- ✅ Compatible with **ESP32 DevKit** and **ESP32-S3 DevKit** modules.  
- ✅ Onboard **DC barrel jack** for 12V input.  
- ✅ **LM2596S-5.0 buck converter** for 12V → 5V regulation.  
- ✅ Separate **3.3V and 5V rails** broken out for peripheral use.  
- ✅ Full GPIO pin access with **clearly labeled headers**.  
- ✅ High-quality capacitors for stable power filtering.  
- ✅ Compact and robust PCB design fabricated via **PCBWay**.  

---

## 🔌 Power Supply Section
- **Input:** 12V DC via barrel jack or external connector.  
- **Regulation:** LM2596S-5.0 step-down converter.  
- **Output Rails:**
  - 5V (primary regulated rail for ESP32 board & peripherals)
  - 3.3V (sourced from ESP32 module regulator)

---

## 📐 Pinout Overview
Both breakout boards expose **all ESP32 GPIOs** through dual headers with silk-screened labels for quick prototyping.


## 🎉 Special Thanks to PCBWay


<div align="center">
  <img src="Assests\photo_2025-09-28_22-46-10.jpg" width="700">
</div>

<p align="center">
  <a href="https://www.pcbway.com/" target="_blank">
    <img src="https://github.com/AvishkaVishwa/12V-DC-Motor-Speed-Controller-PCB-Design-using-KiCAD/blob/0191b6e02eeb30e176867d2a93ebec854536829a/Images/pcbwaylogo.jpg" alt="PCBWay" width="200"/>
  </a>

</p>

I would like to give a huge shoutout and sincere thanks to **[PCBWay](https://www.pcbway.com/)** for sponsoring the PCB fabrication of this project!

The **build quality, silkscreen clarity, via precision, and copper finish** exceeded expectations. PCBWay’s service was fast, professional, and extremely helpful throughout the production process.

This project wouldn’t have been possible without their generous support. If you’re looking to manufacture professional-grade PCBs at an affordable price, I highly recommend checking them out.
