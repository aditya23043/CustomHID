# Custom Ergonomic Input Devices

> Click on the keyboard image to go its github repository

---

## First Iteration (20 keys)

<br><br><p align="center" style="margin-top=10rem;margin-bottom=10rem;"><a href="https://github.com/aditya23043/split_keyboard"><img src="./assets/IMG_5758.jpg" height=auto style="display: block; margin-right: auto; margin-left: auto"></a></p><br><br>

[![20 key keyboard](./assets/IMG_5758.jpg)](https://github.com/aditya23043/split_keyboard)

- Fully Wired (with QMK) or semi-wireless (with custom firmware which is not mature enough)
- AA batteries. (no need to worry about battery degradation that we have with Li-Po batteries)
- MCU: Raspberry Pi Pico W

> [!NOTE]
> [Assembly Video](https://youtu.be/sDFPSLh6BhQ)

### Problems

- 20 keys is too less to implement a practical keymap
- PCB does not have mounting holes for a proper case
- Standard AA batteries are heavy (in the semi-wireless one)

---

## ESD Keyboard (36 keys)

[![esd keeb](./assets/IMG_0150.jpg)](https://github.com/aditya23043/split36)

- Fully Wired only with TRRS port for inter-connectivity
- Proper enclosure to avoid damage to the electronic components
- Hot-swappable MCU: Raspberry Pi Pico W
- Firmware: QMK
- Matured keymap capable of replacing the traditional keyboard fully
- [linkedin post](https://www.linkedin.com/posts/aditya23043_just-completed-my-most-ambitious-project-activity-7335380768921198593-B5wh?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEb0rpkBcvkxpg6PQ2YDkrWiA3oRIAywLL4) (with demo)
 
> [!NOTE]
> [Assembly Video](https://youtu.be/kpw8LIIt7Tc)

### Problems

- For this specific build, I re-used the PCB for both halves due to which
  the TRRS connection to the MCU is reversed. To resolve this, I scratched
  away the copper pads on the PCB and manually connected the TRRS pins to
  the MCU pins
- The TRRS cable is not a common type of cable
- Exposed MCU
- Heat set inserts for mounting can be a bit unstable after frequent
  disassembly

---

## Silent Mechanical Keyboard (36 keys)

[![silent keeb](./assets/IMG_3574.JPG)](https://github.com/aditya23043/split36v2)

- Handwired design without a PCB
- Fully mature enclosure with several screw offsets for structural integrity
- Fully wired keyboard with inter-connection using USB Type-C cable
- Experimented the column splay for the pinky and ring finger for enhanced
  ergonomics
- MCU hidden inside the enclosure and can enter bootloader mode when pressed the case above the mcu.
- Silent mechanical switches
- MCU: Raspberry Pi Pico W
- Firmware: QMK

---

## Cheapino (36 keys)

[![cheapino](./assets/IMG_3587.JPG)](https://github.com/aditya23043/cheap_hw)

- Designed to be a cheap handwired keyboard with just a top and a bottom
  plate for enclosure held together with metal standoffs with the wiring in-between
- It **had** to be a fully wired build due to the budget constraint for this build
- Similar to previous keyboard but with the much smaller Waveshare Rp2040 Zero MCU
- Firmware: QMK
- More aggressive thumb cluster angle along with the pinky and ring finger
  column splay (angle)
- Inter-connectivity between the halves with USB type-c cable

---
