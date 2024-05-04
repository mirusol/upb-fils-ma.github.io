# Pacman Game
The project aims to create a Pacman game along with a Wii remote

:::info 

**Author**: Solomon Miruna-Maria in collaboration with Balba Tudor-Neculai \
**GitHub Project Link**: [Pacman Game](https://github.com/mirusol/upb-fils-ma.github.io/edit/project_documentation/docs/project/2024/miruna.solomon/index.md)

:::

## Description

We're creating a Pac-Man game using two Pico W microcontrollers and a gyroscope sensor for control. Players navigate Pac-Man through the maze by tilting a device, similar to using a Wii Remote. It's a hands-on, motion-controlled gaming experience that adds a new dimension to classic Pac-Man gameplay.

## Motivation

The project was motivated by a desire to explore new avenues in game interaction and enhance the classic Pac-Man experience. Through the integration of Pico W microcontrollers and gyroscope sensors, we aimed to introduce innovative motion-based controls, inspired by gaming console interfaces like the Wii Remote. This curiosity-driven approach fosters experimentation and encourages students to push boundaries in user interface design, aiming to enrich gameplay and user engagement. Additionally, the project offers an opportunity to refine programming skills and explore interdisciplinary collaboration, contributing to continuous improvement and innovation in gaming technology.

## Architecture 

The main components are: 
- 2 pico w
- Modul LCD Driver IC: ILI9341
- 2 USB wires
- Gyroscope and accelerometer GY-6500

## Log

<!-- write every week your progress here -->

### Week 6 - 12 May

### Week 7 - 19 May

### Week 20 - 26 May

## Hardware

Detail in a few words the hardware used.

### Schematics

Place your KiCAD schematics here.

### Bill of Materials

<!-- Fill out this table with all the hardware components that you might need.

The format is 
```
| [Device](link://to/device) | This is used ... | [price](link://to/store) |

```

-->

| Device | Usage | Price |
|--------|--------|-------|
| [Rapspberry Pi Pico W *2](https://www.raspberrypi.com/documentation/microcontrollers/raspberry-pi-pico.html) | The microcontroller | [70 RON](https://www.optimusdigital.ro/en/raspberry-pi-boards/12394-raspberry-pi-pico-w.html) |
| [Modul LCD de 2.8'' cu SPI și Controller ILI9341](https://docs.espressif.com/projects/espressif-esp-iot-solution/en/latest/display/lcd/spi_lcd.html)) | The LCD screen | [70 RON](https://www.optimusdigital.ro/ro/optoelectronice-lcd-uri/3550-modul-lcd-de-28-cu-spi-i-controller-ili9341-240x320-px.html?search_query=lcd+de+2.8+cu+spi&results=56) |
| [Accelerometru și Giroscop](https://docs.nanoframework.net/devicesdetails/Mpu9250/README.html) | The gyroscope | [20 RON](https://www.optimusdigital.ro/ro/senzori-senzori-inertiali/1672-modul-accelerometru-i-giroscop-mpu6500-gy.html?search_query=accelerometru&results=79)|
| [Breadboard HQ]| The board for the remote| [5 RON](https://www.optimusdigital.ro/ro/prototipare-breadboard-uri/44-breadboard-400-points.html?search_query=bread+board&results=147) |
| [Kit Plusivo]| wires and resistors| [50 RON](https://www.optimusdigital.ro/ro/kituri/11254-plusivo-nano-super-starter-kit.html?search_query=plusivo+starter+kit&results=17) |

Total 210 RON

## Software

| Library | Description | Usage |
|---------|-------------|-------|
| [st7789](https://github.com/almindor/st7789) | Display driver for ST7789 | Used for the display for the Pico Explorer Base |
| [embedded-graphics](https://github.com/embedded-graphics/embedded-graphics) | 2D graphics library | Used for drawing to the display |

## Links

<!-- Add a few links that inspired you and that you think you will use for your project -->

 [Pacman Game](https://www.youtube.com/watch?v=rUgfixMTfW8)
...
