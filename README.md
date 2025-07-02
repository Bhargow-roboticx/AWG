# Atmospheric Water Generator (AWG) Project

## 🌦️ Description
This project is an **Atmospheric Water Generator (AWG)** system that extracts water from humid air using Peltier modules and supplies it to plants through an automated irrigation system. It runs completely off-grid using solar energy.

## ⚙️ Components Used
- Arduino Uno / ESP32
- Peltier modules
- CPU fans & heat sink
- 2-channel relay module
- Soil moisture sensor
- Water pump
- 12V SMPS and battery
- Solar panels (Loom Solar 20W x3)
- Smart solar charge controller
- LCD display
- IR sensors

## 🔄 Working Principle
1. Peltier modules cool air to condense water.
2. Water is collected in a UV-sanitized container.
3. A soil moisture sensor checks when to water the soil.
4. Water is pumped to plants only when needed.
5. The system is powered fully by solar panels.

## 📱 App Features
- View temperature and humidity
- Check battery percentage
- Monitor charging status
- Turn ON/OFF components manually
- AI-based automation (coming soon)

## 📊 Circuit Diagram
![Wiring Diagram](docs/wiring_diagram.png)

## 📥 How to Build
1. Connect components as per circuit diagram.
2. Upload `awg_main_code.ino` from the `code/` folder.
3. Install the Android APK from `app/awg_monitor.apk` to monitor the system.
4. Power the system using solar setup.

## 📂 Files Included
- Arduino code in `code/`
- Wiring diagram and documentation in `docs/`
- App APK in `app/`
- Project images in `images/`

## 🔐 License
This project is licensed under the MIT License.

## 📧 Contact
**Author:** Bhargow  
**Email:** bhargow80@gmail.com  
**GitHub:** https://github.com/bhargow80

---

*Inspired by the United Nations Sustainable Development Goals (SDGs):*  
**Goal 6 - Clean Water and Sanitation**  
**Goal 7 - Affordable and Clean Energy**
