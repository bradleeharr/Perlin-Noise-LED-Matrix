# ESP32-64x64-LED-Matrix-Perlin-Noise
Implementation of Perlin noise on a 64x64 LED matrix using an ESP32 microcontroller to generate a natural-looking terrain map

# ESP32-64x64-LED-Matrix-Perlin-Noise

This project is an implementation of Perlin noise on a 64x64 LED matrix using an ESP32 microcontroller. The Perlin noise is used to generate a pseudo-random, natural-looking, continuous noise pattern that can be used for various applications such as terrain generation, texture generation, and more.

## Features

- The project uses Perlin noise to generate a natural-looking, pseudo-random pattern.
- The pattern is displayed on a 64x64 LED matrix.
- The pattern is continuously updated, creating a dynamic visual effect.

## Installation and Running the Project

To run this project, you need to have the ESP32 microcontroller and the necessary libraries installed. The libraries required for this project are `ESP32-HUB75-MatrixPanel-I2S-DMA.h` and `FastLED.h`.

1. Connect your ESP32 microcontroller to your computer.
2. Open the project in your Arduino IDE.
3. Select the correct board and port in the Arduino IDE.
4. Upload the project to your ESP32 microcontroller.


## Credits

This project is adapted from libraries from two sources:

1. [Aurora](https://github.com/pixelmatix/aurora) by Jason Coon
2. [LedEffects Plasma](https://bitbucket.org/ratkins/ledeffects/src/26ed3c51912af6fac5f1304629c7b4ab7ac8ca4b/Plasma.cpp?at=default) by Robert Atkins