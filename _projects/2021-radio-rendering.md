---
layout: project
title: Refrigerator (Dometic CF–35) & Compressor (SECOP BD35F)
description: Analyzing the Thermodynamic Efficiency of a Refrigerator
technologies: Calculations for Efficiency
image: /assets/images/2210Fridge.png
---

| ![Dometic CF–35]({{ "/assets/images/2210Fridge.png" | relative_url }}) | **Refrigerator (Dometic CF–35)**  
Internal volume: 34 L  
Temperature range: +10 °C to –18 °C  
Power supply: 12/24 V DC  
Typical average power draw: 40–60 W  

**Compressor (SECOP BD35F)**  
(From manufacturer datasheet)  
Refrigerant: R-134a  
Nominal compressor input power: 45–60 W  
Cooling capacity at –10 °C evaporating and 45 °C condensing: ~120 W  
Compressor displacement: 2.0 cm³ |
| --- | --- |

---

## Vapor-Compression Refrigeration Cycle

The CF–35 operates on the standard four-stage vapor-compression cycle:

- **Evaporator:** Refrigerant absorbs heat from the refrigerated interior.  
- **Compressor:** Raises refrigerant pressure and temperature.  
- **Condenser:** Rejects heat to ambient air.  
- **Expansion valve:** Throttles refrigerant to low temperature and pressure.  

---

## Cycle State Analysis

![Cycle Analysis]({{ "/assets/images/2210Calcs.png" | relative_url }}){: .inline-image-l}

Using the Work and Thermal Transfer found above, we can find that the fridge has:

- COP (Actual): 2.18  
- COP (Carnot): 4.78  
- COP (Carnot to Actual): 0.46  

![COP Analysis]({{ "/assets/images/2210COP.png" | relative_url }}){: .inline-image-l}

---

## Technologies Used

Calculations for Efficiency
