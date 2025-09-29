# ESP32 & ESP32-S3 Breakout Boards with Onboard Power Supply

When I first started working with the ESP32 and ESP32-S3 DevKits, I noticed a small but frustrating problem: powering them reliably in real projects wasn’t always straightforward.
Most of my projects used 12V supplies (robotics, IoT controllers, lab prototypes), but the DevKits expect 5V or 3.3V. That meant extra converters, messy wiring, and a lot of wasted time.

So I decided to fix that.
I designed these custom breakout boards with a built-in LM2596S-5.0 buck converter, letting me plug in a 12V source directly and instantly get stable 5V and 3.3V rails for the ESP32 and any peripherals.

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

---
## Behind the Build

This was my very first attempt at making custom breakout boards with integrated power. I wanted a board that could accept 12 V directly and step it down to 5 V using the LM2596S buck converter, so I wouldn’t have to juggle external modules.

- Fabrication Experience:
PCBWay’s drill accuracy was especially important here because the DC barrel jack and large electrolytic capacitors needed exact hole alignment. The silkscreen clarity also made labeling all the ESP32 GPIOs readable at a glance, which is essential for prototyping.

- Service Choices:
2-layer board, 1 oz copper.
Standard green solder mask with HASL finish.

---

## 🎉 Special Thanks to PCBWay


<div align="center">
  <img src="Assests\photo_2025-09-28_22-46-10.jpg" width="700">
</div>

<p align="center">
  <a href="https://www.pcbway.com/" target="_blank">
    <img src="https://github.com/AvishkaVishwa/12V-DC-Motor-Speed-Controller-PCB-Design-using-KiCAD/blob/0191b6e02eeb30e176867d2a93ebec854536829a/Images/pcbwaylogo.jpg" alt="PCBWay" width="200"/>
  </a>

</p>

Huge appreciation to **[PCBWay](https://www.pcbway.com/)** for fabricating my ESP32 breakout boards!  
These boards required **accurate drill alignment** for the barrel jack and capacitors, and PCBWay delivered perfectly.  
The **silkscreen clarity** also made every GPIO label easy to read something that’s really important for quick prototyping.

This project wouldn’t have been possible without their generous support. If you’re looking to manufacture professional-grade PCBs at an affordable price, I highly recommend checking them out.
