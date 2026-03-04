# Power Distribution Board — Developer Notes

<!--
  STUB — fill in before activating transclusion.
  Transcluded into: docs/developer/ sections

  Include:
  - Design rationale: why MEAN WELL RD-125A (dual-output, DIN-mount, UL certified)
  - USB-C 5V design: IP2721 + TPS22965 load switch — why this combination
  - Startup sequencing: does 12V or 5V come up first? Does it matter?
  - Inrush management
  - EMI/EMC considerations (AC inlet filter in Schurter module)
  - KiCad project structure and manufacturing notes
-->

!!! info "Content pending"
    This section is being developed.

## Design rationale

_Why MEAN WELL RD-125A was selected over alternatives — coming soon._

## USB-C 5V path

- **IP2721**: USB-C PD negotiation (fixed 5V profile)
- **TPS22965**: Load switch with slew rate control (inrush limiting)
