# 🔧 Microprocessors Application Project

This repository contains the *OLED Module and Tilt Sensor Application* project conducted as part of the microprocessors course. The project covers basic electronics and programming topics such as I2C communication protocol, OLED display control, and tilt sensor integration.

---

## 📜 Project Summary
![](https://github.com/elfaltntas/STM32-SSD1306-LIBRARY-OLED/blob/main/images/urun1-1.jpg)
*Scenario:*
- The value from the tilt sensor is displayed on the OLED screen in the format "PRODUCT: %d".
- As the tilt sensor moves, the counter increases and a green LED lights up.
- When the counter reaches 6, the OLED display shows a "LIMIT!!" warning, a red LED starts flashing, and a buzzer intermittently sounds.

### Project Learning Outcomes
- Usage and control of the OLED Module.
- Applications of the I2C communication protocol.
- Working principles of tilt sensors.

---

## 🛠 Materials Used

- *PinoLab-CodeBoard.Micro*
- *PinARM-STM32F103C8T6*
- *OLED Module (128x64 pixels, 0.96 inch)*
- *Tilt Sensor*
- *Connection cables*

---

## 💡 Project Steps

1. *Hardware Settings:*
   - Necessary pins (PB6, PB7, PB12, etc.) have been configured in STM32CubeIDE.
   - Clock and GPIO settings have been completed.

2. *Library Usage:*
   - The SSD1306 library has been integrated into the project.
   - .h and .c files have been added to the respective folders and made ready for use in the project.

3. *Coding:*
   - Necessary codes have been written in the main.c file in STM32CubeIDE.
   - Tilt sensor and OLED display control have been achieved using HAL GPIO and I2C functions.

4. *Running and Testing:*
   - After making the hardware connections, the project was compiled and tested on the circuit.
   - OLED display outputs were checked based on tilt sensor movements and counter values.

---

## 👥 Contributors
- **Elif Altıntaş**

---

## 📞 Contact

For any questions or collaborations:

- 📧 burhanustubi@gmail.com

