# RC522-RFID-Reader-Module-with-ESP32D
This is a repo for a project with the RC522 which reads &amp;&amp; writes data to a RFID card 

What you need for the project: 
- 1x RC522 RFID module
- 1x Some type of sound emitter / blinking LED
- 1x ESP32
- Connecting Wires

**RFID module PINOUTS**
<br>
<img width="781" height="433" alt="image" src="https://github.com/user-attachments/assets/e70f1fa6-e445-4797-8d66-ef36196fade9" />

**connection sheet**
<br>
<img width="642" height="829" alt="image" src="https://github.com/user-attachments/assets/74ef7bc5-b948-4756-adf3-8f59fe4de27b" />
- the light green wire is a common ground shared by all modules
- the blue wire next to the light green wire is used for powering the ESP32 and is 5V   ( this wire can be replaced by plugging in the usb-C cable to the ESP32 )
- both the buzzer and the RC522 module should be getting 3.3V either from an external power source or from the ESP32

- Any buzzer should work with this setup because buzzers in general aren't very complicated
- the GPIO pins defined in the code may varry so you can change them accordingly to your liking


**if you have a diffrent ESP32 board connect it to the corresponding MISO , MOSI , CLK pins - they will be shown on a ESPs32 pinout in this way**
<img width="988" height="405" alt="image" src="https://github.com/user-attachments/assets/e12f1620-2c7a-4141-be58-2b3a8e0866a0" />
this image is only an example





