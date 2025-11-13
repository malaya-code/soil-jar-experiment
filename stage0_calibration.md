# Stage 0: Jar Calibration

Stage 0 establishes the baseline geometry and mass of the six jars used in the Soil-Jar Experiment. These measurements support later calculations of water retention, mass change, and air displacement during humidity and amendment trials.

## Purpose of Calibration
Accurate internal volume estimates are required before adding soil, liners, or amendments. Measurements focus on empty mass, inner diameter, and usable height. These values define the maximum fillable space and ensure comparability across all experimental stages.

## Measurement Approach
Each jar was cleaned, dried, and weighed on a digital scale. Internal volume was estimated by modeling the jar’s cylindrical section below the shoulder.

### Volume Formula
\[
V_{geom} = \pi \times (d/2)^2 \times h - 10
\]

- d = inner diameter in centimeters  
- h = height of the usable internal column in centimeters  
- 10 cm³ is subtracted to adjust for curvature at the shoulder

## Calibration Table

| jar_id | empty_mass_g | inner_diam_cm | column_height_cm | volume_geom_cm3 |
| --- | ---: | ---: | ---: | ---: |
| Standard-Mason | 244.00 | 7.00 | 12.00 | 451.81 |
| Sq-I-01 | 366.00 | 8.00 | 14.00 | 693.72 |
| Classic-TS-01 | 314.00 | 8.30 | 14.00 | 747.49 |
| Classic-LS-02 | 346.00 | 8.20 | 15.00 | 782.15 |
| PS-00 | 336.00 | 9.00 | 14.00 | 880.64 |
| BB-J | 804.00 | 10.50 | 19.50 | 1678.51 |

## Dataset File
The calibration dataset is stored as `soiljar_stats.sql` and includes the table schema, geometric formula, and all measurement values.
