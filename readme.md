# LED Panel 8x8

This repository contains the KiCad project and documentation for a stackable 8×8 LED matrix module. The design is intended for creating compact LED display tiles that can be chained together to build larger matrices.

## Overview

The module includes a compact 8×8 LED array laid out for standard matrix control. The board is designed with stacking in mind, so several modules can be tiled together to expand the display area while keeping the wiring and layout manageable.

There is no dedicated connector interface on the module. Boards are linked by aligning and soldering their castellated side pads together.

Key characteristics of this project:

- 64 SMD LEDs arranged in an 8×8 matrix
- Stackable module design for building larger LED displays
- KiCad schematic and PCB layout included
- Front and back visuals are available in `docs/`

## Usage

- Use the module with a matrix driver or microcontroller to control rows and columns.
- Chain multiple modules together to create larger display panels.
- Verify the LED current limiting strategy and wiring for your selected driver or controller.

## Project structure

- `module-led-panel-8x8.kicad_pro` — KiCad project file
- `module-led-panel-8x8.kicad_sch` — schematic source
- `module-led-panel-8x8.kicad_pcb` — PCB layout file
- `docs/index.html` — project showcase and documentation page
- `docs/module-led-panel-8x8-front.png` — front view image
- `docs/module-led-panel-8x8-back.png` — back view image
- `docs/module-led-panel-8x8-perspective.png` — perspective view image

## Notes

This repository is focused on the LED matrix module itself. The board layout and connector placement are designed to support display tiling and easy integration into larger LED panel assemblies.
