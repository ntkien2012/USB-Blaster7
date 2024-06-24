# USB-Blaster7

## Introduction
USB-Blaster7 is a project based on Microchip's USB firmware version 2.8. It uses a PIC18F14K50 microcontroller to enable high-speed JTAG communication via SPI. This repository includes all necessary tools such as MPLAB IDE and the C18 compiler.

## Features
- High-speed JTAG communication
- Configurable SPI frequency and IO pin definitions
- Based on stable Microchip USB firmware

## Table of Contents
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Getting Started
### Prerequisites
- MPLAB IDE
- C18 compiler

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/ntkien2012/USB-Blaster7.git
    cd USB-Blaster7
    ```
2. Open the project in MPLAB IDE.
3. Configure the project settings as needed.

## Configuration
Edit the `usb_config.h` and `BlasterMacros.h` files to configure the SPI frequency and IO pin definitions.

## Usage
1. Build the project in MPLAB IDE.
2. Program the PIC18F14K50 microcontroller with the generated firmware.
3. Connect the device to your JTAG interface.

## Contributing
We welcome contributions! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions or feedback, please open an issue on GitHub.

