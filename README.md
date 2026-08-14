# Stmite - Home Automation

![Stmite](stmite.png)

Welcome to the **Stmite** project! This README provides an overview of the project, setup instructions, and other relevant details.

## Table of Contents

- [Visit](#visit)
- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [Structure](#structure)
- [Contributors](#contributors)
- [Contributing](#contributing)
- [License](#license)

## Visit

- [Repository](https://github.com/aabubokarr/stmite)

## About

**Stmite** is an STM32-powered home automation system featuring automated door control, real-time temperature and humidity tracking, ultrasonic distance measurement, and fast UART communication for seamless sensor data flow and local device control.

## Features

- Door Automation
- Humidity and Temperature
- Distance Measurement
- UART Communication

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/aabubokarr/stmite.git
   ```
2. Download the STM32CubeIDE:
   ```bash
   https://www.st.com/en/development-tools/stm32cubeide.html
   ```

## Structure

```
Stmite/
├── others/
│   ├── blink.c              # Onboard blinking in C
│   ├── blink.s              # Onboard blinking in assembly
│   ├── cpulator.s           # Cpulator code
│   ├── external_blink.s     # External LED blinking
│   └── main.s               # Assembly entry point and main program logic
├── first.c                  # First experimental/program module
├── fiveseven.c              # Door, Humidity and Distance code
├── fonts.c                  # Font data used for display output
├── LICENSE                  # project's license
├── README.md                # Project documentation
├── second.c                 # UART signal receiver code
└── syscalls.c               # System-call implementations
```

## Contributors

<p align="center">
  <a href="https://github.com/aabubokarr/stmite/graphs/contributors">
    <img src="https://contrib.rocks/image?repo=aabubokarr/stmite" alt="Contributors" />
  </a>
</p>

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
