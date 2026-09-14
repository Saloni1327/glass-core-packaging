# Glass Core Packaging for Heterogeneous Integration

**ECE 4883/8883 — Glass Core Packaging**  
Georgia Institute of Technology | Spring 2026

### End-to-End Fabrication and Characterization of a Glass-Core Package Substrate

## Overview

This project involved the end-to-end fabrication and characterization of a **glass-core package substrate for heterogeneous integration**.

Starting with an AGC EN-A1 glass substrate, the fabrication workflow integrated dielectric lamination, thin-film metallization, photolithography, copper electroplating, through-glass via (TGV) formation, die embedding, planarization, and via-in-via fabrication.

The fabricated structures were evaluated using multiple characterization techniques, including laser profilometry, white-light interferometry (WLI), X-ray imaging, Shadow Moiré warpage measurement, and LCR electrical characterization of on-package passive devices.

The project provided hands-on experience across the complete advanced-packaging process flow, connecting **materials processing, microfabrication, metrology, and electrical characterization**.

---

## Process Flow

The fabrication workflow integrates redistribution-layer formation with through-glass via fabrication, die embedding, planarization, and via-in-via processing.

### Part A — Redistribution Layer (RDL) Fabrication

1. **ABF Dielectric Lamination**
   ABF GL-102 dielectric film was laminated and cured on the glass substrate.

3. **Surface Preparation & Seed Layer Deposition**  
   Ar/O₂ reactive ion etching (RIE) was used for surface preparation, followed by sputter deposition of a Ti/Cu seed layer.

4. **Photolithography**  
   Dry-film negative photoresist was patterned using maskless lithography to define the redistribution-layer features.

5. **Copper Electroplating**
    
![Copper Electroplating](figures/copper_electroplating.png)

   Copper was selectively electroplated into the patterned photoresist mold to form the RDL.

6. **Photoresist Stripping & Seed-Layer Removal**  
   The photoresist and exposed Cu/Ti seed layers were removed to isolate the patterned copper traces.

### Part B — TGV Formation & Die Embedding

6. **Through-Glass Via (TGV) & Cavity Formation**  
   Femtosecond laser machining was used to fabricate TGVs and the die cavity in the glass substrate.

7. **Die Placement & Embedding**  
   A die was aligned and placed inside the laser-machined cavity using a flip-chip bonding system.

8. **ABF Encapsulation**  
   Additional ABF dielectric layers were laminated around the embedded die.

9. **Flycut Planarization**  
   Diamond flycutting was used to reduce surface non-uniformity and improve substrate planarity.

10. **Via-in-Via Formation**  
    Laser ablation was used to form vias through the ABF within the TGV footprints for subsequent interconnection.

    ---

    ## Characterization & Metrology

Multiple techniques were used to evaluate the fabricated glass-core package throughout the process flow.

- **Laser Profilometry** — evaluated RDL surface topography, feature dimensions, step height, and surface roughness.
- **White-Light Interferometry (WLI)** — measured glass surface roughness and 3D surface topography around the embedded-die cavity.
- **X-ray Imaging** — non-destructively inspected the internal package structure, die/ABF interface, and TGV alignment.
- **Shadow Moiré** — measured room-temperature substrate warpage and coplanarity.
- **LCR Characterization** — electrically characterized on-package capacitors and evaluated connectivity through the package.
- **Thickness Metrology** — quantified total thickness variation (TTV) before and after flycut planarization.

These measurements connected fabrication-process parameters with the structural, dimensional, and electrical performance of the package.

---

## Key Results

The completed fabrication and characterization workflow demonstrated several key outcomes:

- Successfully resolved **100/100 µm Cu RDL line/space features** at a 200 µm pitch.
- Achieved approximately **5–6 µm electroplated Cu thickness**.
- Measured a glass surface roughness of **0.850 nm Ra** using WLI.
- Reduced substrate **total thickness variation (TTV) from 31 µm to 6 µm** through flycut planarization.
- Achieved room-temperature package **coplanarity of 15 µm**, within the reported JEDEC warpage specification.
- Measured approximately **8–10 µm TGV positional offset** and ~8 µm via-in-via alignment error.
- X-ray inspection showed **no observed voids or delamination** at the die/ABF interface.
- LCR measurements produced consistent values for the large square capacitors, while anomalous measurements helped identify **open-via connectivity failures**.

Overall, the project demonstrated an end-to-end glass-core packaging process integrating fine-pitch redistribution layers, through-glass vias, embedded dies, planarization, and package-level characterization.

---

## Process Challenges & Engineering Insights

Several fabrication challenges provided important insights into process control and manufacturability:

- **ABF material handling:** Premature embrittlement of the ABF dielectric highlighted the importance of controlled storage conditions and material handling prior to lamination.
- **Die-cavity planarity:** Resin flow into the gap between the embedded die and cavity produced an approximately 20 µm surface depression, emphasizing the importance of die-to-cavity dimensional tolerances.
- **Via-in-via alignment:** An approximately 8 µm alignment error demonstrated the sensitivity of multilayer laser processing to stage positioning, substrate mounting, and optical alignment.
- **Planarization:** Flycut processing substantially reduced substrate thickness variation, demonstrating its importance before subsequent metallization and lithography.
- **Electrical continuity:** LCR measurements showed how abnormal electrical responses can be used diagnostically to identify open-via failures.

These observations highlighted the close relationship between **materials behavior, process tolerances, metrology, and package reliability** in glass-core packaging.

---

## Skills & Techniques

**Advanced Packaging & Microfabrication**
- Glass-core packaging
- ABF dielectric lamination
- Reactive ion etching (RIE)
- Ti/Cu sputter deposition
- Photolithography
- Copper electroplating
- Femtosecond laser micromachining
- Through-glass via (TGV) fabrication
- Die embedding and flip-chip placement
- Flycut planarization
- Via-in-via fabrication

**Characterization & Metrology**
- Laser profilometry
- White-light interferometry (WLI)
- X-ray inspection
- Shadow Moiré warpage measurement
- Surface roughness and thickness metrology
- LCR electrical characterization

**Engineering Concepts**
- Heterogeneous integration
- Redistribution layers (RDL)
- Fine-pitch interconnects
- Process integration
- Package warpage and planarity
- Electrical continuity and failure analysis

---

## Conclusion

This project demonstrated the end-to-end fabrication and characterization of a glass-core package substrate for heterogeneous integration.

The completed process integrated **fine-pitch Cu redistribution layers, through-glass vias, embedded-die packaging, ABF dielectric processing, and precision planarization**. Characterization confirmed substantial improvement in substrate thickness uniformity after flycutting, acceptable room-temperature warpage, and structural integrity at the embedded die/ABF interface.

The project provided practical experience in integrating **materials processing, microfabrication, dimensional metrology, and electrical characterization** within an advanced semiconductor-packaging workflow.
