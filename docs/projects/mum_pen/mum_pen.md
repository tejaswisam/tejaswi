---
tags:
  - ESP32
  - 3D Printing
  - Fusion 360
  - CAD Modeling
  - Electronics
  - Sensors
---
# Multi-Utility Measuring Pen (Patent Pending)
> :octicons-location-16: Developed at IIITDM Kancheepuram &nbsp;
> :material-calendar: Jan 2024 - Apr 2024 &nbsp;

## Introduction
I designed and developed Multi-Utility Measuring Pen (MUM-Pen), a device that combines a writing tool and a measuring instrument in one. The MUM-Pen has two sides: writing side and measuring side. The writing side can be used to take notes, markings, sketches, or diagrams. The measuring side uses an encoder to measure the distance between two points and a digital display to display it.

![MUM_Pen](MUMPen_v62.png){ width="500" loading=lazy } ![MUM_Pen](image.png){ width="400" loading=lazy }

## Working
It uses an encoder for determining distance between two points. It sends signal to ESP-32 microcontroller, that maps the encoder output signal and convert it to distance travelled. Microcontroller will get power from rechargeable Lithium-ion battery, which will be charged by a solar panel.

![MUM_Pen](mum_pen.png){ width="400" loading=lazy } ![MUM_Pen](mum_pen.gif){ width="200" loading=lazy }