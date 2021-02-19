# Microcontroller-Project
ANTITHEFT SYSTEM FOR BIKES
1 Introduction
Uppsala is a student town where the bike is the most common means of transport for most of the students. Also, Bike theft is a common issue in the city. The objective of this project is to design an Antitheft system based on the knowledge gained by this course. This system is very cost effective and promising.

2 Hardware Components
2.1 Atmega 328
The Atmel 8-bit AVR RISC-based microcontroller combines 32 kB ISP flash memory with read-while-write capabilities, 1 kB EEPROM, 2 kB SRAM, 23 general purpose I/O lines, 32 general purpose working registers, three flexible timer/counters with compare modes, internal and external interrupts, serial programmable USART, a byteoriented 2-wire serial interface, SPI serial port, 6-channel 10- bit A/D converter (8-channels in TQFP and QFN/MLF packages), programmable watchdog timer with internal oscillator, and five software selectable power saving modes. The device operates between 1.8- 5.5 volts. The device achieves throughput approaching 1 MIPSper MHz.[1]

2.2 24 PIN LCD ADAPTOR
The adapter has 4 buttons in it which we used for our project as the input buttons. The output which reads as dots states that the program code is running and If there is a value it will get us an output stating “On” or else it keeps sending “dots”. The Buttons were connected from the LCD display to the Micro controller as per the connections shown in Lab 2. The schematic diagram of the connections are towards the end of the document.

2.3 TILT SENSOR
The tilt sensor has a metallic ball inside which acts as a switch. When the ball is on one end, the circuit is closed and vice-versa. when the sensor is disturbed, based on the position of the ball, values are sent to the micro controller. [2]

2.4 GTPA010 GPS Receiver (Future Scope)
The Global Top FGPMMOPA6C is an ultra-compact POT (Patch On Top) GPS Module, The module utilizes the  MediaTek new generation GPS Chipset MT3339 that achieves the industry’s highest level of sensitivity (-165dBm ) and instant Time-to-First Fix (TTFF) with lowest power consumption for precise GPS signal processing to give the ultra-precise positioning under low receptive, high velocity conditions.Up to 12 multi- tone active  interference canceller (ISSCC2011 award), customer can have more flexibility in system design. Supports up to 210 PRN channels with 66 search channels and 22 simultaneoustracking channels, FGPMMOPA6C supports various location and navigation applications, including autonomous GPS, SBAS(note) ranging (WAAS, EGNO, GAGAN, MSAS), AGPS. FGPMMOPA6C is excellent low power consumption characteristic (acquisition 82mW, tracking 66mW), power sensitive devices, especially portable applications. [3]

5 Conclusion
We were able to interface the microcontroller with the tilt sensor and 24 pin display. there are two possibilities to raise an alarm. One is upon entering the incorrect code or Forcefully moving the bike. This could be detected by using the value of the Tilt sensor.The only way to turn off the alarm is by entering the correct code.we were happy to witness the working of this protocol and presented the same in the project presentation. the GPS receiver sensor was also interfaced and the outcome was seen on the CRO in the lab. The future scope of this project would be to use GSM and get the current location of the Bike on the users Mobile device.

References
[1] microchip. (2019) Atmega328. Accessed: 2019-02-10. [Online]. Available:
https://www.microchip.com/wwwproducts/en/ATmega328
[2] B. Ellison. (2019) How do tilt sensors work? Accessed: 2019-02-10. [Online].
Available: https://www.azosensors.com/article.aspx?ArticleID=318
[3] G. Tech. (2019) Fgpmmopa6c gps standalone module data sheet. Accessed:
2019-02-10. [Online]. Available: https://cdn-shop.adafruit.com/datasheets/
GlobalTop-FGPMMOPA6C-Datasheet-V0A-Preliminary.pdf

