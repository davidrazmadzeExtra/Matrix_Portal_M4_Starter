# Matrix Portal M4 - Starter Guide

# Description

This is a starter guide for the Matrix Portal M4 with LED Display. We will connect to your local network and to test the connection. The WiFi connection will be important for future projects.

### Product Link - $69.95: [Adafruit Matrix Portal Starter Kit - ADABOX 016 Essentials](https://www.adafruit.com/product/4812?gclid=Cj0KCQiA-JacBhC0ARIsAIxybyPBieJQcynPl2pXjvab7hVEQsTwaz4hQDPrLauBzb0ygXunag1x8hQaAkM3EALw_wcB)

### Complete Guide - [AdaBox 016 - Tutorials](https://learn.adafruit.com/adabox016)

<hr />

# Guide

We will be following this guide: https://learn.adafruit.com/adafruit-matrixportal-m4+

## 1. Prep the MatrixPortal

Connect power to the matrix display panel using the power terminals. Also install to the board via the connectors.

https://learn.adafruit.com/adafruit-matrixportal-m4/prep-the-matrixportal

## 2. Install CircuitPython

We will drag a `.uf2` file into the `MATRIXBOOT` Volume to get a `CIRCUITPY` drive where we can edit files.

`cp adafruit-circuitpython-matrixportal_m4-en_US-7.3.3.uf2 /Volumes/MATRIXBOOT`

https://learn.adafruit.com/adafruit-matrixportal-m4/install-circuitpython

## 3. Download CircuitPython Libraries

Download and extract the zip file and drag several folders into `CIRCUITPY/lib` to get started.

`cp -r adafruit_matrixportal adafruit_portalbase adafruit_esp32spi neopixel.mpy adafruit_bus_device adafruit_requests.mpy adafruit_fakerequests.mpy adafruit_io adafruit_bitmap_font adafruit_display_text adafruit_lis3dh.mpy adafruit_minimqtt /Volumes/CIRCUITPY/lib`

https://circuitpython.org/libraries

## 4. Install the Mu Editor

This is the recommended editor you should be using for CircuitPython development.

https://learn.adafruit.com/welcome-to-circuitpython/installing-mu-editor

## 5. Connect to the Internet

Create a `secrets.py` file on your `CIRCUITPY` drive and then upload the `code.py` to connect to the Internet using WiFi.

https://learn.adafruit.com/adafruit-matrixportal-m4/internet-connect

<hr />
