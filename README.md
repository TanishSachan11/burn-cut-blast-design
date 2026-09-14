# Burn Cut Design — Underground Blasting Calculations

Blast design calculations and presentation for a burn-cut round in underground blasting.

## Files

- **`mid_points_burncut.xlsx`** — Full calculation workbook:
  - Cut section charge calculations (Q1–Q4)
  - Rest-hole charges (floor, wall, roof, stoping)
  - Total charge, rock volume, and **powder factor**
  - **Kuz-Ram fragmentation estimate** (mean fragment size X50)
  - **PPV / vibration check** using the USBM scaled-distance model, including safe standoff distances

- **`Burn_Cut_Presentation_CV.pptx`** — Slide deck walking through the design: hole layout, cut-section theory, charge calculations, final results, and the fragmentation/vibration estimates above.

## Key results

| Quantity | Value |
|---|---|
| Total explosive charge (Q_total) | 92.30 kg |
| Rock volume per round | 58.8 m³ |
| Powder factor | 1.570 kg/m³ |
| Mean fragment size (X50, Kuz-Ram) | ≈ 7.6 cm |
| Safe standoff @ 50 mm/s PPV limit | ≈ 18 m |
| Safe standoff @ 5 mm/s PPV limit | ≈ 75 m |

## Notes / assumptions

- Kuz-Ram rock factor `A = 10` is assumed for competent hard rock — refine with site-specific rock mass data if available.
- USBM constants `K = 1140`, `B = 1.6`, and max charge/delay `W = 6.4 kg` are typical/illustrative values — calibrate against monitored test-blast vibration records for a real site.
- All calculated cells in the workbook are live formulas, not hardcoded values, so changing an input (hole diameter, explosive density, burden, etc.) propagates through the whole sheet.
