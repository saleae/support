---
title: Setup
sidebar: mydoc_sidebar
permalink: setup.html
folder: getting-started
summary:
---

The Saleae Logic Analyzer is a powerful tool capable of capturing multiple signals from a digital circuit and displaying that information in the form of timing diagrams. Saleae’s _Logic_ software can help you decode a variety of digital protocols, including UART, SPI, I2C, 1-Wire, I2S, CAN, USB, and many more. These features can make debugging your embedded designs much simpler.

To begin, download and install the _Logic_ software from [Saleae's downloads page](https://www.saleae.com/downloads/).

If you do not have a logic analyzer, you can still try out the _Logic_ software with simulated data. Once _Logic_ starts, simply click **Start Simulation**.

Connect one or more cable harnesses to the Saleae Logic Analyzer. Note that each cable harness has an arrow on the top of the connector. This arrow should point up \(same side as the Saleae logo\) and to the left \(the side with the ‘S’ in Saleae\).

![](https://saleae.github.io/support/images/setup/setup1.jpg)

The unlabeled black wires are ground \(GND\), and the signal wires are labeled 0-8 \(repeated if you have the Logic Pro 16\). Looking straight at the ports of the analyzer, the top row of pins are labeled 0-8.

![](https://saleae.github.io/support/images/setup/setup2.png)

Build your test circuit, connect at least one ground wire to your circuit's ground node, and connect one or more signal wires to the nodes you wish to measure.

![](https://saleae.github.io/support/images/setup/setup3.jpg)



{% include links.html %}