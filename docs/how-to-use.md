# How to use Microbit More

## Preparation of the micro:bit

### 1. write a program to the micro:bit
Connect the micro:bit to your computer with a USB cable, and write the latest program for Microbit More to the micro:bit. (You only need to write the program to the micro:bit once, and after that, you can connect the micro:bit only by using Scratch.)

Program for Microbit More [microbit-mbit-more-v2-0_2_3.hex](https://github.com/microbit-more/pxt-mbit-more-v2/releases/download/0.2.3/microbit-mbit-more-v2-0_2_3.hex)

### 2. Adjusting the direction sensor of the micro:bit
Immediately after writing the program, "TILT TO FILL SCREEN" will be displayed on the LED screen to adjust the direction sensor. Tilt the micro:bit back and forth, left and right, so that all the LEDs are glowing. (You will not be able to connect the scratch until you have completed this adjustment.)

## Connect the micro:bit.

### 1. Open Microbit More

Open https://microbit-more.github.io/editor in your web browser.
(If you are using a browser that does not support the Web Bluetooth API (such as FireFox or Safari), install and run [Scratch Link](https://scratch.mit.edu/microbit) on that computer.)

### 2. Find your micro:bit

Press the Connect button in the 'Microbit More' category to find a nearby micro:bit with Microbit More written on it.

![](microbit_more-connect_button-disconnected.png)

### 3. Select your micro:bit

Select the name of the micro:bit you want to connect (the 5 alphabet letters that run on the LED) from the list of micro:bits and press 'Pairing'.
When the connection is established, press the "Go to Editor" button.

### 4. Confirm the connection.

Click "Show pattern ♡" to see which micro:bit is connected.

____
## Connecting via USB

Press the Connect button while holding down the "Shift" key to select the USB connection.
(micro:bit v2, [microbit-mbit-more-v2-0_2.hex](https://github.com/microbit-more/pxt-mbit-more-v2/releases/tag/0.2.2) or later)

Since it uses the [Web Serial API](https://wicg.github.io/serial/), it is currently only available for Chrome/Edge on Chromebooks/Mac/Windows.

***Caution***.
Communication is unstable in the current version.
Sensor values are available, but if you use blocks with commands such as analog level or LED display continuously, the communication will fail after about 10 minutes.