# AtArduinoCore-sam
ArduinoCore-samd modified to work with "TFG Zero" SAML21G18B board.<br>
Based on ArduinoCore-samd modifications and added MCU support from [mattairtech](https://github.com/mattairtech/ArduinoCore-samd) and [Electronic Cats](https://github.com/ElectronicCats/ArduinoCore-samd).

## Installation
1. Replace Arduino's Atmel-CMSIS SAML21B `\component` folder located at<br>
`C:\Users\<username>\AppData\Local\Arduino15\packages\arduino\tools\CMSIS-Atmel\1.2.0\CMSIS\Device\ATMEL\saml21b\include\component`<br>
with [this folder](https://github.com/Atalonica/AtArduinoCore-sam/raw/main/component.zip) (unzip it first).
2. Open Arduino IDE and add new board support by going to `File > Preferences` and adding the next URL:<br>
`https://raw.githubusercontent.com/Atalonica/AtArduinoCore-sam/main/package_arduino_index.json`<br>
into `Additional Boards Manager URLs`.
3. Go to `Tools > Board: > Boards Manager...` and search and install "Atalonica SAMx Boards".<br><br>
 
If you see `CRC doesn't match, file is corrupted.` error, try again as it is probably a bug.

## Additional libraries
- [LowPowerLab's RFM69](https://github.com/LowPowerLab/RFM69/)
- [Atalonica's SecureRF](https://github.com/Atalonica/SecureRF) (AEAD based on Xoodyak)
- Atalonica's DS28C16
- Atalonica's DS2477
