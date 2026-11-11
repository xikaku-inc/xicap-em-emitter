# References

Datasheets are not stored in this repository; fetch them from the manufacturer.

| Part | Role | Source |
|---|---|---|
| Premo 3DCC28-A-0150J | emitter coil (3D Coil Cube, Tx antenna) | [grupopremo.com product page](https://grupopremo.com/products/3dcc28-a), datasheet linked there (General Catalogue 2024, p. 234) |
| Premo 3DV15-A-S0900J | pickup coil in the XiCAP receiver | Premo General Catalogue 2024, p. 220 (SMD 3D Coil, Rx) |
| Premo 3DCC20-A | smaller alternative emitter coil | [grupopremo.com AR/VR coils](https://grupopremo.com/collections/ar-vr-coils) |

Values used in the plan, read from the 3DCC28 datasheet:

| Code | L (X/Y/Z) | Q at 20 kHz | SRF min | DCR max | Field at 1 m, 20 kHz, 0.25 A rms |
|---|---|---|---|---|---|
| 3DCC28-A-0039J | 380 / 375 / 365 µH | 31 / 30 / 28 | 1500 kHz | 1.4 Ω | 6.9 nT |
| 3DCC28-A-0150J | 1.49 / 1.46 / 1.39 mH | 46 / 46 / 46 | 200 kHz | 3.0 / 2.9 / 3.2 Ω | 8.9 nT |

Both 39.5 × 39.5 × 38.6 mm, through-hole, −20 to 85 °C. The datasheet does not say in which
direction the 1 m field figure is taken.

Standards referred to:

- ICNIRP, Guidelines for limiting exposure to time-varying electric and magnetic fields
  (1 Hz to 100 kHz), Health Physics 99(6), 2010. The 27 µT general-public reference level quoted
  in the plan is from memory and must be checked against the published table before any design
  decision rests on it.
