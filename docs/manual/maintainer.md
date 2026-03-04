# Power Distribution Board — Maintainer Notes

<!--
  STUB — fill in before activating transclusion.
  Transcluded into: docs/maintenance/hardware/power-distribution.md

  Include:
  - PSU specs: MEAN WELL RD-125A (12V@7.7A + 5V@7.7A)
  - 12V bus: 10× 5.5×2.1mm barrel jack outputs, load assignments
  - 5V bus: 2× USB-C (IP2721 + TPS22965), load assignments
  - AC inlet: Schurter 6200.5521 panel-mount module
  - Fuse ratings and replacement procedure
  - Output voltage measurement points and acceptance range (e.g. 12V ±5%)
  - Inrush current at power-on (affects fuse selection)
  - Board replacement procedure
  - PCB layout notes (thermal, trace width for high-current paths)
-->

!!! info "Content pending"
    KiCad schematic entry in progress — design spec locked.

## Power rails

| Rail | Source | Nominal | Max load | Outputs |
|---|---|---|---|---|
| 12 V | MEAN WELL RD-125A | 12 V | 7.7 A | 10× barrel jack (5.5×2.1mm) |
| 5 V | MEAN WELL RD-125A | 5 V | 7.7 A | 2× USB-C (IP2721 + TPS22965) |

## AC inlet

Schurter 6200.5521 panel-mount power entry module. Includes IEC 60320 C14 inlet, fuse holder, and switch.

## Load assignments

_Which barrel jack feeds which board — coming soon (pending schematic entry)._
