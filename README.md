![Redbox banner](https://raw.githubusercontent.com/ThatRedBox/.github/refs/heads/main/brand/Redbox_banner.png)

<img src="documentation//Edgeberry_Explorer_Cartridge_rendering.png" align="right" width="40%"/>

The **Redbox Explorer Hardware Cartridge** is designed for easily connecting sensors, actuators, and other peripherals to your system. It features the widely used 4-pin 2.0 mm pitch JST-PH connector, compatible with modules and breakouts from popular ecosystems like [Grove](https://www.seeedstudio.com/catalogsearch/result/?q=grove), [Crowtail](https://www.elecrow.com/catalog/category/view/s/crowtail/id/13/), and [STEMMA](https://www.adafruit.com/category/1005).

#### Ports:
- **5x Digital in/out** (with PWM on D1)
- **2x Analog input** (0-5V)
- **1x UART**
- **2x I2C**

<br clear="right"/>

## Layout

| Port     | Connection             | Info |
|----------|------------------------|------|
| **D1**   | GPIO12 <br/>GPIO20     | PWM     |
| **D2**   | GPIO21 <br/>GPIO16     |      |
| **D3**   | GPIO13 <br/>GPIO24     |      |
| **D4**   | GPIO25 <br/>GPIO22     |      |
| **D5**   | GPIO23 <br/>GPIO27     |      |
| **A1**   | *ADC* CH0 <br/>*ADC* CH1  |      |
| **A2**   | *ADC* CH2 <br/>*ADC* CH3  |      |
| **I2C**  | I2C SDA <br/>I2C SDL   |      |
| **UART** | UART RX <br/>UART TX   |      |

>[!WARNING]
>The digital I/O lines on this Hardware Cartridge use a passive N-MOSFET level-shifting circuit designed for compatibility with standard open-drain and push-pull I/O configurations.

On the Hardware Cartridge board is an ADC chip (MCP3008) connected with the SPI interface.

## Examples

The **[Crowtail Demo](https://github.com/Edgeberry/Edgeberry-HWCartridge-EdgeExplorer/tree/main/examples/Crowtail-Demo)** example is a basic but essential IoT demo with [Crowtail](https://www.elecrow.com/catalog/category/view/s/crowtail/) hardware breakouts and the [Node-RED](https://nodered.org/docs/getting-started/raspberrypi) low-code programming environment.

## License & Collaboration
**Copyright© 2024 Sanne 'SpuQ' Santens**. This project is released under the **CERN OHL-W** license. Rules & guidelines apply to the usage of the Redbox brand.

### Collaboration

If you'd like to contribute to this project, please follow these guidelines:
1. Fork the repository and create your branch from `main`.
2. Make your changes and ensure they adhere to the project's design style and conventions.
3. Test your changes thoroughly.
4. Ensure your commits are descriptive and well-documented.
5. Open a pull request, describing the changes you've made and the problem or feature they address.
