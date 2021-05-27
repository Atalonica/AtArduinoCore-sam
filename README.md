# AtArduinoCore-sam
ArduinoCore-samd modified to work with "TFG Zero" SAML21G18B board.<br>
Based on ArduinoCore-samd modifications and added MCU support from [mattairtech](https://github.com/mattairtech/ArduinoCore-samd).

## Installation
1. Open Arduino IDE and add new board support by going to `File > Preferences` and adding the next URL:<br>
`https://raw.githubusercontent.com/Atalonica/AtArduinoCore-sam/main/package_arduino_index.json`<br>
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
Fork based on development and modifications by MattairTech LLC and Electronic Cats and Atalonica.


```
- MIT License -

Copyright (C) 2021 Atalonica.

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.


- LGPL License -

Copyright (c) 2015 Arduino LLC.  All right reserved.
Copyright (c) 2017-2018 MattairTech LLC. All right reserved.

This library is free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public
License as published by the Free Software Foundation; either
version 2.1 of the License, or (at your option) any later version.

This library is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
See the GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public
License along with this library; if not, write to the Free Software
Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA
```
