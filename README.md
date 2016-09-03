## RFStamp

RFStamp is a small form factor SAMR21G18 Radio Module Hardware.

### Features

-- SAMR21G18 MCU: Cortex M0+ CPU up to 48MHz, 256kB flash, 32kB RAM, IEEE 802.15.4 radio, capacitive touch.
-- 4-Mbit DataFlash for data and firmware image storage. Up to 64Mbit pin compatible.
-- Dual row 100mil extesion header.
-- Through hole or SMD mounting (no USB for SMD).
-- 15 configurable GPIO/peripheral pins.
-- Micro-USB connector.
-- Standard 10-pin Cortex Debug connector.
-- Green user LED.
-- Reverse power protection.
-- Supply voltage range 1.8V (without LDO) to 5.5V.
-- Input voltage measurement.
-- Capacitive touch pins with as much clearance as possible to minimize ground loading.

### Design Environment

Device has been designed with Altium Designer 16. Supporting documentation is in Microsoft Excel format.

### Device Variants

-- Through hole.
-- SMD - No USB, as USB connector and components are placed on the bottom.

### Configuration

-- USB Powered - To make the device USB powered, resistor R6 (0 ohm) needs to be mounted.
-- Direct battery powered - Mount resistor R7 and remove U2. This allows to save power and voltage dropout on LDO. MCU supply voltage is 1.8V-3.3V.

### Compatibility

-- Arduino Zero - As Arduino is using the same MCU (R21 = D21 + RF) it might be possible to use Arduino environment for development. This has not been investigated.

### Software

Currently no board specific software is provided.

### Software Tools and Libraries

-- [Atmel Studio IDE](http://www.atmel.com/tools/ATMELSTUDIO.aspx)
-- [Free ZigBee Pro stack - BitCloud](http://www.atmel.com/tools/BITCLOUD-ZIGBEEPRO.aspx)
-- [IEEE 802.15.4 MAC](http://www.atmel.com/tools/IEEE802_15_4MAC.aspx)
-- [SmartConnect 6LoWPAN](http://www.atmel.com/tools/SmartConnect-6LoWPAN.aspx)

### License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.



