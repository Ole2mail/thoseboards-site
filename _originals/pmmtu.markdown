---
title: pmMTU
date: 2017-05-08 09:55:00 Z
position: 23
layout: page
---

**Stage:** ready
![002-pmMTU-side.jpeg](/uploads/pmMTU/002-pmMTU-side.jpeg)
![001-pmMTU-top.jpeg](/uploads/pmMTU/001-pmMTU-top.jpeg)

**Overview:**
pmMTu is a PMOD(TM) interface compatible telemetry module providing microampere current as well as voltage consumption readings for testing IoT device. IoT device supposed to be powered through the pmMTu module bypass connectors. 2 pins are for supply power (XS1), other 2 pins are for the IoT device connection (XS2).

**Features:**
* pmMTu1V8 tuned for 0­1.8V voltage range, 0­50mA current measurement range if J1 is shortened or 0­500uA current measurement range if J2 is shortened
* pmMTu1V8 has 138mA max current peak survivable limit
* pmMTu3V3 tuned for 0­3.3V voltage range, 0­50mA current measurement range if J1 is shortened or 0­500uA current measurement range if J2 is shortened
* pmMTu3V3 has 75mA max current peak survivable limit
* both versions could withstand up to 6V on supply measurement power pins
* both versions do positive/negative voltage based milliampere measurement with 50/32768 ~ 1.52e­3 mA or 1.52e­6 A step for 0­50mA range (J1 shortened)
* both versions do positive/negative voltage based microampere measurement with 500/32768 ~ 1.52e­8 uA or 1.52e­14 A step for 0­500uA range (J2 shortened)
* pmMTu1V8 operates on constant 3.3V regulated DC supplied over standard PMOD port
* pmMTu3V3 require constant 5V regulated DC supplied over PMOD port and is recommended to be chained with special pm5V0 DC­DC regulator pass­through module
* both versions provide constant incoming supply voltage reading with the help of first ADS1110
* both versions provide constant milli/microampere current consumption reading with the help of second ADS1110
* both ADS chips are different address based i2c interface and chained on the same i2c bus encapsulated inside PMOD interface

**Documentation**

[View schematic in PDF](/uploads/pmMTU/SCH_Assembly_pmMTu.pdf)

Assembly chains with this board

![assembly chain - pmMTu3V3+pm5V0+pmTPS+pm3V3+pmCLK+pmUSBUART2.png](/uploads/pmMTU/assembly%20chain%20-%20pmMTu3V3+pm5V0+pmTPS+pm3V3+pmCLK+pmUSBUART2.png)

Also, see related videos on 
[Youtube](https://www.youtube.com/playlist?list=PLPUxs94yXWxffdO9a-trBPxHUxIWgIJw5)

Part number for pmMTu3V3: 302301

![003-pmMTU-bottom.jpeg](/uploads/pmMTU/003-pmMTU-bottom.jpeg)