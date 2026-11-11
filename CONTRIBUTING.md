# Contributing

Thanks for looking at this. The project is at the planning stage, so the most valuable
contributions are reviews of the reasoning, measurements of the parts, and alternative designs
with their numbers.

## How to contribute

- **Question a number.** Open an issue that names the section of `docs/plan.md`, states the figure
  you doubt and shows your own derivation or measurement. Datasheet references help.
- **Propose an alternative.** A different driver, coil, frequency plan or sync method is welcome
  as an issue or a pull request against `docs/`, as long as it carries the same kind of numbers
  the plan does: drive voltage, current range, harmonics, exposure, cost.
- **Measurements.** If you have one of the coils, measurements of L, Q, AC resistance and the
  inter-axis coupling factor between 15 and 30 kHz would settle several open questions.

## Conventions

- Units are SI with a space before the unit (100 mA rms, 21 kHz, 0.78 V peak).
- Every figure that is calculated says what it was calculated from. Every figure that is measured
  says how.
- Hardware files are KiCad (version 10 or later). Keep symbol and footprint libraries inside the
  project.
- Firmware, when it exists, builds from the command line without an IDE.
- No customer or partner names in this repository. The emitter is described in terms of what it
  does and what it connects to.

## Licensing of contributions

By submitting a contribution you agree that it is licensed under the same terms as the material it
modifies: CERN-OHL-W-2.0 for hardware, CC BY 4.0 for documentation, and the license declared in
`firmware/` for firmware.
