# Delta Robot with Magnetic Gripper

## Overview

This project involves the design and development of a Delta Robot equipped with a magnetic gripper. The robot is designed to perform high-speed pick-and-place tasks using a simple yet effective structure. The project is divided into two main parts: the structural design and the control system.

## Table of Contents

- [Description of Materials](#description-of-materials)
- [Hardware List](#hardware-list)
- [PCB Specifications](#pcb-specifications)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Description of Materials

The materials used in this project are essential for the integrity and functionality of the Delta Robot. The materials are categorized into two main sections: the designed structure of the robot and the control part.

### Robot Structure and Material

| **Robot Part**    | **Material**         |
|-------------------|----------------------|
| Fixed Part        | Wood (Laser Cutting) |
| Upper Base        | Wood (Laser Cutting) |
| Arms              | PLA (3D Printing)    |
| Joints            | PLA (3D Printing)    |
| Conveyor Belt     | Rexene               |
| Conveyor Body     | Acrylic (Laser Cutting) |
| Gripper           | Magnetic             |

The structure of the robot is made from carbon, metal rods, and plastic, with several parts being 3D printed to ensure precision and durability. The magnetic gripper is designed to handle ferromagnetic materials efficiently.

## Hardware List

Below is a list of hardware components used in the project:

| **Equipment**             | **Model**  | **Quantity** |
|---------------------------|------------|--------------|
| Servo motor               | MG90X      | 3            |
| Arduino UNO               | -          | 1            |
| PCB                       | -          | 1            |
| Miscellaneous Components  | -          | 25           |
| DC Motor (Geared)         | -          | 1            |
| Magnetic Gripper          | -          | 1            |

### PCB Specifications

- **Dimensions:**
  - Length: 3.94 inches
  - Width: 3.94 inches
- **Silkscreen:** Yes, on both sides
- **Material:** FR4, 35 µm Cu, 0.0629 inch thickness

## Installation

To set up the Delta Robot project:

1. Clone the repository: `git clone https://github.com/your-username/delta-robot-with-magnetic-gripper.git`
2. Follow the wiring diagram provided in the `docs` folder.
3. Upload the Arduino code from the `src` folder to the Arduino UNO using the Arduino IDE.
4. Assemble the robot structure using the materials and parts listed above.

## Usage

Once the setup is complete, you can run the Delta Robot using the provided control software. The magnetic gripper can be activated to pick and place ferromagnetic materials with precision. Detailed instructions for operation and troubleshooting can be found in the `docs` folder.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.
