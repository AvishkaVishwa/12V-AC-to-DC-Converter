# AC to DC Converter Circuit

## Overview

This project demonstrates a simple **AC to DC converter** circuit that converts an AC voltage input into a smooth DC voltage output. The circuit is based on a full-wave rectifier bridge, filtering components, and an LED indicator for power status.

## Schematic and PCB Layout

- The circuit uses **four diodes (D1, D2, D3, D4)** to form a **full-wave rectifier bridge**, which converts the incoming **AC (Alternating Current)** signal into a **DC (Direct Current)** output.
- A **capacitor (C1, 1000µF)** acts as a **filter capacitor**, smoothing out the rectified DC signal by reducing any remaining ripple.
- The circuit includes an **LED (D5)**, accompanied by a **current-limiting resistor (R1, 2.2kΩ)**, which indicates when the circuit is powered.
- A second resistor **(R2, 10kΩ)** is included for additional functionality, potentially for voltage division or a secondary operation within the circuit.
- The **AC input** is connected via the screw terminals labeled **J1** on the left side of the board, and the **DC output** is available at the screw terminals labeled **J2** on the right side.

### PCB Design

- The **PCB layout** shows the copper traces that connect the diodes, capacitor, resistors, and LED components.
- The design uses **through-hole components** for easy assembly.
- The traces for **ground (GND)** and **positive voltage output (+VE)** are clearly marked to ensure proper wiring during assembly.

## Operation

- The circuit accepts an **AC voltage input** and converts it to **DC voltage** through the full-wave rectifier bridge (formed by the four diodes).
- The **filter capacitor (C1)** smooths the rectified output to reduce ripple and provide a cleaner DC signal.
- The **LED** serves as a **power indicator**, lighting up when the circuit is operational.

## Features

- **Full-Wave Rectifier**: Converts AC to DC with the help of four diodes.
- **Ripple Reduction**: The 1000µF capacitor reduces ripple, providing a stable DC output.
- **LED Power Indicator**: Provides a visual confirmation that the circuit is receiving power and functioning properly.

## How to Use

1. Connect the AC input source to the terminals labeled **AC in**.
2. Attach your DC-powered device to the terminals labeled **DC out**.
3. When power is supplied, the **LED** will light up, indicating the circuit is functioning.
4. The output voltage can be measured at the **DC out** terminals to verify the conversion from AC to DC.

## Components

- **Diodes**: 4 x 1N4007
- **Capacitor**: 1 x 1000µF
- **Resistors**:
  - R1: 2.2kΩ (current-limiting resistor for LED)
  - R2: 10kΩ
- **LED**: Power indicator
- **Screw Terminals**: 2 x Screw_Terminal_01x02 (for AC input and DC output)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
