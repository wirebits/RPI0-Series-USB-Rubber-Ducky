# RPI0-Series-USB-Rubber-Ducky
Setup for Raspberry Pi Zero Series boards to make a USB Rubber Ducky.

# Supported Boards
- Raspberry Pi Zero
- Raspberry Pi Zero W
- Raspberry Pi Zero 2 W

>[!TIP]
>Use at least `8GB` Micro SD Card.<br>
>When use new Micro SD Card then format it as FAT32.<br>
>Make sure that Micro USB cable supports Data transfer.

# Installation and Setup of Circuit Python
1. Downloadb latest CircuitPython `.DISK.IMG.ZIP` file :
   - Raspberry Pi Zero - [here](https://circuitpython.org/board/raspberrypi_zero/)
   - Raspberry Pi Zero W - [here](https://circuitpython.org/board/raspberrypi_zero_w/)
   - Raspberry Pi Zero 2 W - [here](https://circuitpython.org/board/raspberrypi_zero2w/)
2. Download Raspberry Pi Imager according to your Operating System from [here](https://www.raspberrypi.com/software/).
3. Simply install it.
4. Connect Micro SD Card (at least 8GB) to the computer.
5. Open Raspberry Pi Image.
6. Click on `Choose Device` and select the board from the list which you have.
7. Click on `Choose OS` and at the bottom click on `Use Custom`.
8. Select the downloaded `.DISK.IMG.ZIP` from the computer.
9. Click on `Choose Storage` and select the Micro SD Card.
10. Click on `Next`.
11. Click on `No`.
12. Click on `Yes`.
13. Wait for sometime and after that `.DISK.IMG.ZIP` is successfully flashed into the Micro SD Card.
14. Unplug the Micro SD Card from the computer and plug into the board.
15. Connect Micro USB Cable to the `USB` port of the board.
    - Make sure that Micro USB cable supports Data transfer.
    - It is connected as `CIRCUITPY`.
    - Means CircuitPython is successfully flashed in the Raspberry Pi Zero Series Board.
16. Open `CIRCUITPY`.
   - There are two important things in it : `lib` folder and `code.py` file.
17. Download latest Adafruit CircuitPython Bundle from [here](https://github.com/adafruit/Adafruit_CircuitPython_Bundle/releases)
18. Extarct the ZIP file.
19. Go to the `lib` folder in the extracted ZIP file.
20. Copy `adafruit_hid` folder in the `lib` folder of `CIRCUITPY`.
21. Done! Now, Raspberry Pi Pico Series Board is ready to use as a USB Rubber Ducky.
