# AtArduinoCore-samL
ArduinoCore-samd modified to work with "TFG Zero" SAML21G18B board (added support for the built-in TRNG).<br>
Based on ArduinoCore-samd modifications and added MCU support from [mattairtech](https://github.com/mattairtech/ArduinoCore-samd).

## Installation
1. Open Arduino IDE and add new board support by going to `File > Preferences` and adding the next URL:<br>
`https://raw.githubusercontent.com/Atalonica/AtArduinoCore-samL/main/package_atalonica_index.json`<br>
into `Additional Boards Manager URLs`.
3. Go to `Tools > Board: > Boards Manager...` and search and install "Atalonica SAML Boards".<br><br>
 
If you see `CRC doesn't match, file is corrupted.` error, try again as it is probably a bug.

## Additional libraries
- [LowPowerLab's RFM69](https://github.com/LowPowerLab/RFM69/)
- [Atalonica's SecureRF](https://github.com/Atalonica/SecureRF) (AEAD based on Xoodyak)
- Atalonica's DS28C16
- Atalonica's DS2477

## Licenses

This core has been developed by Arduino LLC in collaboration with Atmel.
Fork based on development and modifications by MattairTech LLC and Atalonica.
See [LICENSE](https://github.com/Atalonica/AtArduinoCore-samL/blob/main/LICENSE) file.
