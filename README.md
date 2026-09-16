# pcb-project


🦋 Butterfly USB Hub Dongle

This is a small 4-port USB hub built into a butterfly-shaped PCB. Instead of using a cable like most USB hubs, it plugs directly into the side of a laptop.

I wanted to make something a more compact usb that can be used for anything I need, so I designed mine as a dongle and I wanted it to work with newer laptops that mostly use USB-C as well as older ones that still have USB-A.

The board has a male USB-C connector and a male USB-A connector for the laptop side. You only use one of them at a time depending on what port your laptop has.


I also wanted the PCB itself to be part of the design rather than just a rectangular board, so I shaped it like a butterfly and plan to add a UV-printed gradient design to it as a challenge. 

The PCB is 1.2 mm thick to work with the edge-mount USB connectors.

Why I Made It

I use devices with both USB-A and USB-C, and I thought it would be useful to have one small hub that could plug into either type of laptop without needing another adapter or cable. I also wanted to try designing my first PCB for practice. 

I started by following the Macondo USB hub tutorial to understand how a USB hub circuit works. From there, I changed the design, I added both USB-C and USB-A upstream connectors, changed it into a direct-plug dongle, designed the butterfly-shaped PCB, and added my own visual design.

This project has also helped to learn KiCad and understand how the schematic, PCB layout, footprints, connectors, and physical board shape all have to work together.

How to Use It

1. Plug either the USB-C or USB-A connector into your laptop. Only one should be connected at a time.
2. Plug USB-A devices into the three USB-A ports on the board.
3. A USB-C device can also be connected to the USB-C port on the hub.

* Hub IC: CoreChips SL2.1S
* USB standard: USB 2.0
* Upstream: 1 × male USB-C + 1 × male USB-A
* Downstream: 3 × female USB-A + 1 × female USB-C
* PCB: 2-layer, 1.2 mm thick
* Size: about 75 mm × 65 mm
* Board shape: custom butterfly
* External power: not required
