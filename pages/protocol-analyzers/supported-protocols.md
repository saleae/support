---
title: Supported Protocols
sidebar: mydoc_sidebar
permalink: supported-protocols.html
folder: protocol-analyzers
summary:
---

The Saleae Logic software includes the following protocol analyzers:

<iframe width="560" height="315" src="https://www.youtube.com/embed/8V122EwwEGc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

* Asynchronous Serial
* I2C 
* SPI \(Serial Peripheral Interface\)
* CAN \(Controller Area Network\)
* DMX512
* I2S Audio / PCM
* Manchester, Differential Manchester, Bi-Phase Space, and Bi-Phase Mark
* 1-Wire
* Synchronous Parallel
* UNI/O
* JTAG
* PS2 Keyboard & Mouse
* Atmel SWI \(Single Wire Interface\)
* LIN \(Local Interconnect Network\)
* BISS-C
* MDIO \(Management Data Input/Output\)
* USB Low Speed and Full Speed
* HDMI-CEC
* SMBus \(includes PMBus and Smart Battery\)
* HDLC \(High-Level Data Link Control\)
* Modbus RTU & ASCII
* MIDI
* HD44780 Parallel LCD
* SWD \(ARM Serial Wire Debug\)

### **More Protocol Analyzers**

Some Logic users have created their own protocol analyzers. The following list of analyzers are available but not officially supported by Saleae.

### **Do all Saleae logic analyzer models support these protocols?**

Yes. However, you will need to use a device with sufficient bandwidth to record the original signal. For instance, Logic 4 simply does not have the bandwidth required to capture and decode USB full speed. Logic 4 has a maximum digital bandwidth of 3 MHz, and USB full speed requires a digital bandwidth of at least 12.5 MHz.


{% include links.html %}
