# Octoboard

An ATmega328P-PU development board designed from scratch in KiCad for prototyping AVR projects without breadboard mess. It uses only THT components to simplify soldering, and does not use an onboard serial chip to save on cost and simplicity

Octoboard breaks out all the GPIO from the chip, and provides all power management and supporting hardware.

The BOM is for 5 boards, as that is the minimum I can buy from JLCPCB and some parts

Built for the Hack Club Stardance YSWS program

---

## Visuals

### Renders

| Front | Back | Angle |
| ----  | ---- | ----- |
| ![Front](/images/render-front.png) | ![Back](/images/render-back.png) | ![Angle](/images/render-angle.png) |

### PCB

| All Layers | Front Layer | Back Layer |
| ---------- | ----------- | ---------- |
| ![All Layers](/images/pcb.webp) | ![Front Layer](/images/pcb-front.png) | ![Back Layer](/images/pcb-back.png) |

### Explainer Video

[![OctoBoard Promo](http://img.youtube.com/vi/EGtcOqKRJP8/0.jpg)](http://www.youtube.com/watch?v=EGtcOqKRJP8 "Octoboard Promo")

---

## Design and Specs

*   **Microcontroller** ATmega328P-PU (DIP-28 package)
*   **Clock speed** External 16 MHz crystal oscillator
*   **I/O** All GPIO pins broken out to standardized 2.54mm pitch female headers
*   **Power management** Steps down barrel jack or input voltage to clean filtered 5v for the chip, and broken out for components

---
