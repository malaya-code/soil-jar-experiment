# Soil-Jar Calibration (Stage 0) — Methods and Data: Cardboard & Humidity Soil Revitalization Experiment

## **Overview**

The Soil-Jar Experiment examines how recycled cardboard liners, controlled humidity pulses, and low-cost amendments influence the reactivation of microbial and fungal activity in dry indoor soil. Six jars serve as small, repeatable environments that allow direct observation of humidity effects, liner behavior, and early biological changes. The design prioritizes accessible methods and consumer-grade tools so that home researchers can reproduce the workflow without specialized equipment.

* * *

## **Purpose**

The project aims to build a reliable, low-cost method for revitalizing dry soil in indoor settings.

  
Cardboard liners, simple household amendments, and controlled humidity cycles are tested as potential supports for microbial activation and early soil recovery. The approach is meant to be replicable for small-space gardeners and independent researchers.

* * *

## **Methods Summary**

### Experimental Setup

- Six glass jars (~480 mL) with loosely fitted lids.
    
- Liner material: plain kraft cardboard or printed cardboard.
    
- Amendments: none, coffee grounds, or crushed pine cone.
    
- Water dose: 30 mL per jar.
    

### Humidity Routine

Baseline humidity levels are currently being recorded with the humidifier off to establish control conditions.

  
Stage 1 will introduce a daily 10-minute cool-mist pulse using a consumer ultrasonic humidifier, Pure Enrichment MistAire, 1.7 L tank. A ThermoPro TP50 hygrometer records environmental changes before and after each pulse.

### Measurements

| Parameter | Device | Frequency |
| --- | --- | --- |
| Relative humidity (%) | ThermoPro TP50 | pre / post / +10 min |
| Temperature | ThermoPro TP50 | daily |
| Fungal activity (0–3) | visual scoring | daily |
| Condensation band height (cm) | ruler | daily |
| Moisture mass (g) | digital scale ±0.1 g | weekly |
| pH  | 3-in-1 soil meter | start and end |
| Moisture reading | 3-in-1 soil meter | start and end |

* * *

## **Stage 0: Jar Calibration**

Stage 0 establishes the geometric volume and baseline mass of each jar.  
These measurements support later calculations of moisture retention, mass changes, and air displacement.

&nbsp;

**Volume calculation**

\[  
V_{geom} = \\pi \\times (d/2)^2 \\times h - 10  
\]

where:

- *d* = inner diameter in centimeters
    
- *h* = usable internal height in centimeters
    
- 10 cm³ is subtracted to correct for shoulder curvature
    

Dataset file: `data/soiljar_stats.sql`

* * *

## **Repository Structure**

```
soil-jar-experiment/
│
├── README.md
├── LICENSE
│
├── data/
│   ├── soiljar_stats.sql
│   └── soiljar_humidity.csv   (upcoming)
│
└── docs/
    ├── methods_v0.1.md
    ├── stage0_calibration.md
    └── notes.md
```

* * *

## **Planned Stages**

1.  Stage 0 — Jar calibration
    
2.  Stage 1 — Humidity cycling
    
3.  Stage 2 — Amendment testing
    
4.  Stage 3 — Soil preparation
    
5.  Stage 4 — Microbial growth assessment
    

Each stage will add a corresponding dataset and documentation file.

* * *

## **Contact**

Research inquiries: [eutopia.research@proton.me](mailto:eutopia.research@proton.me)  
ORCID: https://orcid.org/0009-0000-0059-9445
