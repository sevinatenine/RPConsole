# Design ideas

For the RPConsole!

## Console

- A small game console
- Using the RP2350

## Part ideas

- Possibly with the [Pimoroni Pico Lipo 2 XL W](https://shop.pimoroni.com/products/pimoroni-pico-lipo-2-xl-w)
    - Has WiFi (2.4GHz) / Bluetooth
    - 16MB flash, 8MB PSRAM
    - USB-C (for serial, game contoller / Other HID)
- Battery powered (LiPo/Lithium Ion)
- With color touchscreen, 3.2 inch - from [sparkfun](https://www.sparkfun.com/color-320x240-touchscreen-3-2-inch-ili9341-controller.html).
    - 480x320
        - Enough for NES and SNES
    - Touch sceen

## Games

- Can play NES and SNES games
- Can play custom games too
- Sprig games (possibly)?
- Other game emulation for certain versions

## Streaming/Controlling

- Stream games from PC to the console
    - Custom PC app -> (Over USB serial) -> Console
    - Custom PC app -> (WiFi) -> Console
- Stream games from the console to the PC
    - Console -> (Over USB serial) -> Custom PC app
    - Console -> (WiFi) -> Custom PC app
- Use the console as a controller for the PC
    - Console -> (Over USB HID game controller) -> PC
    - Console -> (Over WiFi) -> Custom PC app
    - Console -> (Over bluetooth - wireless controller) -> PC
- Use the PC as a contoller for the console (POSSIBLY)
    - Custom PC app -> (Over USB serial) -> Console

## Game loading

- Downloading a game from the PC
- Uploading a game to the PC
- Down(/up)loading a game from one console to another

## Game play

- Single player
- Multi player (One is host, one is device)
    - Between consoles with Bluetooth
    - Between consoles with WiFi
    - Between consoles with USB serial

## Controls

- D-pad
- A, B, X, Y
- Trigger buttons
- Start button
- Select button

## Sound

- Sound slider
- Tiny speaker (PWM???)
- Audio amplifier??
- Headphone jack??

## Other things

- Brightness slider?
- Stylus maybe?