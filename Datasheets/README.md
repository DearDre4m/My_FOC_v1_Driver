Component datasheets and hardware reference documents.
# Component Datasheets

Official manufacturer datasheets and technical references for the **My_FOC_v1_Driver** project.

This project is a custom three-phase BLDC motor driver based on the Texas Instruments DRV8313, featuring three-phase current sensing and an external reference-voltage circuit.

## 1. Main ICs

| Component | Manufacturer | Description | Official Datasheet |
|---|---|---|---|
| DRV8313 | Texas Instruments | Three-phase motor driver | [Download PDF](https://www.ti.com/lit/ds/symlink/drv8313.pdf) |
| INA181A1 | Texas Instruments | Bidirectional current-sense amplifier, 20 V/V gain | [Download PDF](https://www.ti.com/lit/ds/symlink/ina181.pdf) |
| TLV9001 | Texas Instruments | Rail-to-rail operational amplifier | [Download PDF](https://www.ti.com/lit/ds/symlink/tlv9001.pdf) |

## 2. Official Product Pages

- **DRV8313:** https://www.ti.com/product/DRV8313
- **INA181:** https://www.ti.com/product/INA181
- **TLV9001:** https://www.ti.com/product/TLV9001

## 3. Passive Components and Connectors

The PCB also contains:

| Component | Specification |
|---|---|
| Current sensing resistors | 0.03 Ω |
| Reference voltage resistors | 10 kΩ |
| Ceramic capacitors | 10 nF, 100 nF and other values |
| Bulk capacitor | 22 µF / 35 V |
| Pluggable terminal blocks | KF2EDG series, 3.5 mm pitch |

Manufacturer-specific datasheets for these components will be added after their exact part numbers are confirmed.

## 4. Notes

- Always refer to the latest official manufacturer documentation.
- Verify component package, pinout, voltage rating and current rating before assembly.
- The hardware is currently at revision V1 and has not yet been physically validated.
- Third-party datasheets remain the intellectual property of their respective manufacturers.

## 5. Project Repository

[My_FOC_v1_Driver](https://github.com/DearDre4m/My_FOC_v1_Driver)
