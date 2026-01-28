# INTenX Power Distribution Board

Power distribution board for test fixtures.

## Project Structure

- `intenx-power-distribution-board.kicad_pro` - KiCad project file
- `intenx-power-distribution-board.kicad_sch` - Schematic
- `intenx-power-distribution-board.kicad_pcb` - PCB layout

## CI/CD

This project uses GitHub Actions for automated:
- Schematic PDF export
- BOM generation
- PCB fabrication outputs (gerbers, drill)
- DRC checks
- 3D renders
- JLCPCB-ready outputs via KiBot

## Usage

Open with KiCad 9.0+
