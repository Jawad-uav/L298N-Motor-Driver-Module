# L298N Dual Motor Driver

Custom PCB design of the popular L298N dual H-bridge motor driver module, designed from schematic to PCB layout in Altium Designer.

<p align="center">
  <img src="L298N%20Altium%20Project%20Files/Export%20Documents/Pictures/L298N%20Motor%20Driver%20Module%20User%20Manual.png" alt="L298N Motor Driver Module" width="700">
</p>

## Features

- Dual-channel H-bridge for controlling two brushed DC motors
- Current-sense resistors for both motor channels
- 8 flyback/freewheeling diodes for motor protection
- Motor direction/status LEDs for both channels
- Power supply indication LEDs
- Onboard 5 V regulator for the L298N logic supply
- Selectable onboard or external 5 V supply
- Independent motor direction and PWM control
- Dedicated motor and power screw terminals
- Logic control header for IN1–IN4, ENA and ENB
- M4 mounting holes
- High-current PCB routing for motor supply and outputs

## Design

The schematic and PCB were designed in **Altium Designer**, with the circuit based on the **STMicroelectronics L298 datasheet and application circuit**.

The PCB uses separate routing considerations for high-current motor paths, 5 V power, and control/sense signals. A ground plane is used to improve power and signal return paths.

## Tools

- Altium Designer
- Custom schematic and PCB libraries
- PCB 3D modeling

## References

- [STMicroelectronics L298 Datasheet](https://www.st.com/resource/en/datasheet/l298.pdf)
- [STMicroelectronics L298 Product Page](https://www.st.com/en/motor-drivers/l298.html)

## Note

This project is a custom implementation inspired by the widely available **L298N motor driver modules**, with additional features such as dual current sensing and motor direction indication.
