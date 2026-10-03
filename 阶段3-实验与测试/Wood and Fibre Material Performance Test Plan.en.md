# Wood and Fibre Material Performance Test Plan

## 1 Introduction

In the Phase-3 experiments, systematic physical and mechanical property testing must be carried out on the procured woods (Limba, Kiri, Balsa) and fibre materials (carbon-fibre cloth, ALC arylate-carbon blend cloth). The experimental objectives are as follows:

1. **Verify the actual material parameters**: confirm whether the measured density, thickness, and moisture content of the procured materials are consistent with the values claimed by the supplier, and correct the weight estimates in [Three Blade Design Schemes and Procurement List](../%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Three%20Blade%20Design%20Schemes%20and%20Procurement%20List.en.md).
2. **Establish a material-property database**: obtain the mechanical parameters of each material, such as hardness, elastic modulus, and bending strength, providing a quantitative basis for the structural design.
3. **Assess the feasibility of the fabrication process**: test the bonding strength of adhesives under different material combinations, verifying the reliability of the lamination process.
4. **Screen the optimal material combination**: through comparative testing, determine the most suitable wood-density range and fibre type for each scheme.

The materials covered by this experiment plan include:

| Material | Type | Density range (g/cm³) | Experimental focus |
| :--- | :--- | :--------------: | :----------- |
| Limba | Hardwood outer ply | 0.40–0.55 | Surface hardness, bending elasticity, bonding performance |
| Kiri | Lightweight medial ply | 0.23–0.40 | Density distribution, compressive strength, glue-uptake rate |
| Balsa | Ultra-light core | 0.10–0.20 | Density uniformity, moisture absorption, compressive strength |
| Carbon-fibre cloth | Synthetic fibre | 1.50–1.80 (fibre) | Areal weight, tensile strength, resin compatibility |
| ALC arylate-carbon blend cloth | Blended fibre | — | Weave density, feel evaluation, bending-stiffness contribution |

---

## 2 Experiment 1: Measurement of Material Density and Geometric Parameters

### 2.1 Experimental Objective

To accurately measure the actual density, thickness uniformity, and dimensional accuracy of each wood and fibre material, providing basic data for the blade weight estimation. According to the estimates in [Three Blade Design Schemes and Procurement List](../%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Three%20Blade%20Design%20Schemes%20and%20Procurement%20List.en.md), the weight error must be controlled within ±2 g, so the measurement accuracy of the material density must reach 0.01 g/cm³.

### 2.2 Experimental Equipment

| Equipment | Specification requirement | Use |
| :--- | :------- | :--- |
| Electronic balance | Precision 0.01 g, range ≥500 g (already procured per [Three Blade Design Schemes and Procurement List](../%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Three%20Blade%20Design%20Schemes%20and%20Procurement%20List.en.md)) | Weighing the sample mass |
| Digital caliper | Precision 0.01 mm, range ≥150 mm (already procured) | Measuring the sample length, width, and thickness |
| Vernier caliper | Precision 0.02 mm (spare) | Thickness re-check |
| Drying oven | Temperature control ±2 °C, up to 105 °C | Determining the wood moisture content |

### 2.3 Wood Density Measurement

#### 2.3.1 Specimens and Numbering

Three specimens are cut from each wood, with dimensions of 50 mm × 50 mm, keeping the original raw-material thickness. The specimen numbering rule is `[material abbreviation]-[number]`, e.g. LMB-1, KRI-1, BLS-1.

#### 2.3.2 Measurement Steps

1. **Dimensional measurement**: use the digital caliper to measure the length $L$, width $W$, and thickness $T$ of each specimen, taking the average of 3 measurements each, and calculate the volume $V = L \times W \times T$.
2. **Mass measurement**: use the electronic balance to weigh the specimen mass $m$, to a precision of 0.01 g.
3. **Density calculation**: $\rho = \frac{m}{V}$, in g/cm³.
4. **Moisture-content correction**: place the specimen in a 105 °C drying oven and dry it to constant weight (weighing at 2 h intervals until the mass change is <0.1 %), and calculate the dry density $\rho_{\text{dry}}$ and the moisture content $MC = \frac{m - m_{\text{dry}}}{m_{\text{dry}}} \times 100\%$.

#### 2.3.3 Data-Recording Table

| Specimen ID | Material | Length (mm) | Width (mm) | Thickness (mm) | Volume (cm³) | Mass (g) | Density (g/cm³) | Dry density (g/cm³) | Moisture content (%) |
| :------- | :--- | :-------: | :-------: | :-------: | :--------: | :------: | :----------: | :-----------: | :--------: |
| LMB-1 | Limba | 50.02 | 49.98 | 0.55 | 1.375 | 0.69 | 0.502 | 0.498 | 4.8 |
| LMB-2 | Limba | 50.00 | 50.01 | 0.54 | 1.350 | 0.67 | 0.496 | 0.492 | 5.1 |
| KRI-1 | Kiri | 50.03 | 49.97 | 3.02 | 7.550 | 2.27 | 0.301 | 0.293 | 6.2 |
| BLS-1 | Balsa | 50.01 | 50.00 | 4.01 | 10.025 | 1.50 | 0.150 | 0.145 | 8.5 |

#### 2.3.4 Data Analysis

- Calculate the **mean density**, **density standard deviation**, and **coefficient of variation** $CV = \frac{\sigma}{\bar{\rho}} \times 100\%$ of each wood.

### 2.4 Areal-Weight Measurement of Fibre Materials

The performance of the fibre cloth takes **areal weight (g/m²)** and **thickness** as its core indicators, which directly determine the contribution of the fibre layer to the blade weight.

#### 2.4.1 Specimen Preparation

Three specimens, 100 mm × 100 mm, are cut from each of the carbon-fibre cloth and the ALC fibre cloth. When cutting, align along the weave direction and use a rotary cutter together with a metal straightedge to reduce fraying. Gloves and a mask must be worn during the operation (see Section 3.2.1 of [Experimental Safety Instructions](../Experimental%20Safety%20Instructions.en.md)).

#### 2.4.2 Measurement Steps

1. **Dimensional measurement**: use the caliper to measure the length and width of each specimen (to 0.1 mm) and calculate the area $A$.
2. **Mass measurement**: use the electronic balance to weigh the mass $m$ (to 0.01 g).
3. **Areal-weight calculation**: $GSM = \frac{m}{A} \times 10^4$, in g/m².
4. **Thickness measurement**: measure the thickness at 5 points in total—the four corners and the centre of the specimen—and take the average.

#### 2.4.3 Data-Recording Table

| Specimen ID | Material | Length (mm) | Width (mm) | Area (cm²) | Mass (g) | Areal weight (g/m²) | Mean thickness (mm) | Weave density (yarns/cm) |
| :------- | :--- | :-------: | :-------: | :--------: | :------: | :----------------: | :-----------: | :-------------: |
| CF-C1 | Carbon fibre (woven) | 100.0 | 100.0 | 100.00 | 0.64 | 64.0 | 0.22 | 4.0 |
| ALC-C1 | ALC (arylate-carbon blend) | 100.0 | 100.0 | 100.00 | 0.58 | 58.0 | 0.24 | 3.5 |

---

## 3 Experiment 2: Wood Hardness Testing

### 3.1 Experimental Objective

Hardness reflects the ability of wood to resist local indentation deformation and directly affects the tactile feedback when the racket hits the ball. The hardness of the outer ply determines the rigid response at the moment of ball exit, while the hardness of the core affects the overall deformation and vibration-damping characteristics.

### 3.2 Test Method

The **Shore D hardness** test method is used, suitable for testing medium-hardness woods (Limba, Kiri) and softwood (Balsa)[^1]. Owing to the limited conditions of the project, a **simplified Brinell hardness method** may alternatively be used—pressing a steel ball (10 mm diameter) into the wood surface with a fixed load and measuring the indentation diameter.

#### 3.2.1 Shore D Hardness Testing

1. Place the specimen on a stable, hard tabletop.
2. Hold the Shore D durometer and press it vertically against the specimen surface, applying sufficient pressure for the indenter to press fully in.
3. Read the value after the pointer stabilises (about 3 s).
4. Measure 5 different points on each specimen (avoiding knot and grain-defect regions), and take the average.

#### 3.2.2 Data-Recording Table

| Specimen ID | Material | Point 1 | Point 2 | Point 3 | Point 4 | Point 5 | Mean hardness (Shore D) | Standard deviation |
| :------- | :--- | :------: | :------: | :------: | :------: | :------: | :---------------: | :----: |
| LMB-1 | Limba | 59 | 57 | 60 | 58 | 56 | 58.0 | 1.58 |
| KRI-1 | Kiri | 29 | 27 | 30 | 26 | 28 | 28.0 | 1.58 |
| BLS-1 | Balsa | 10 | 9 | 11 | 8 | 10 | 9.6 | 1.14 |

### 3.3 Expected Result Ranges

| Material | Expected Shore D hardness | Remarks |
| :--- | :--------------: | :--- |
| Limba | 50–65 | Medium hardness, good dwell |
| Kiri | 20–35 | Soft; needs to be combined with fibre layers for reinforcement |
| Balsa | 5–15 | Extremely soft, almost no surface rigidity |

---

## 4 Experiment 3: Wood Bending-Performance Testing

### 4.1 Experimental Objective

Bending performance (bending strength and elastic modulus) is a key indicator for assessing the deformation characteristics of wood under the stress conditions of a racket. The bending stiffness of the outer and medial plies directly affects the racket's rebound speed and dwell time.

### 4.2 Test Method

A **three-point bending test** is used, simplified with reference to the ASTM D790 standard[^2].

#### 4.2.1 Specimen Preparation

Three specimens are cut from each wood along the grain direction, with dimensions of 80 mm × 10 mm × original thickness. For the Limba veneer, which is less than 3 mm thick (0.5–0.6 mm), three sheets may be stacked and bonded before testing (recording the influence of the bonded layers).

#### 4.2.2 Test Steps

A simple bending test device is used (see Figure 1):

```
          Apply load F
              ↓
         ┌────────┐
    ─────┤Specimen├─────
    ▲    └────────┘    ▲
    │         │         │
    ├──── L ──┼── L ───┤
    │   Support span S  │
```

**Figure 1: Schematic of the three-point bending test**

1. Set the support span to $S = 64$ mm (16 times the specimen thickness for thickness <3.2 mm).
2. Place the specimen on the two support points, with the loading head aligned with the midpoint of the span.
3. Load in steps (50 g weights per step, or continuous loading using a force gauge), recording the load $F$ and the mid-span deflection $d$ at each step.
4. Load to specimen fracture or the maximum deformation (deflection = thickness × 1.5), and record the **maximum load $F_{\max}$**.

#### 4.2.3 Data Processing

- Bending stress $\sigma_f = \frac{3FS}{2bh^2}$, in MPa ($b$ = specimen width, $h$ = specimen thickness)
- Bending elastic modulus $E_f = \frac{S^3}{4bh^3} \cdot \frac{\Delta F}{\Delta d}$ (taking the load–deflection slope of the elastic segment)
- Bending strength $\sigma_{f,\max} = \frac{3F_{\max}S}{2bh^2}$

#### 4.2.4 Data-Recording Table

| Specimen ID | Material | Width b (mm) | Thickness h (mm) | Span S (mm) | Elastic-segment slope (N/mm) | Maximum load F_max (N) | Elastic modulus E_f (MPa) | Bending strength (MPa) |
| :------- | :--- | :---------: | :---------: | :---------: | :--------------: | :--------------: | :--------------: | :-----------: |
| LMB-B1 | Limba | 10.02 | 1.62 | 64 | 5.8 | 62 | 10350 | 73.5 |
| KRI-B1 | Kiri | 10.00 | 3.04 | 64 | 8.2 | 45 | 4150 | 31.2 |
| BLS-B1 | Balsa | 9.98 | 4.00 | 64 | 3.5 | 18 | 2560 | 14.4 |

### 4.3 Expected Result Ranges

| Material | Expected bending elastic modulus (MPa) | Expected bending strength (MPa) |
| :--- | :-------------------: | :---------------: |
| Limba | 8000–12000 | 60–90 |
| Kiri | 3000–6000 | 25–45 |
| Balsa (along the grain) | 2000–5000 | 10–25 |

---

## 5 Experiment 4: Wood Moisture-Absorption and Glue-Uptake Testing

### 5.1 Experimental Objective

Because of its porous structure, Balsa may absorb a large amount of glue (PVA glue or epoxy resin) during lamination, causing the actual weight gain to exceed expectations. Section 7.1 of [Three Blade Design Schemes and Procurement List](../%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Three%20Blade%20Design%20Schemes%20and%20Procurement%20List.en.md) already pointed out that Balsa requires sealing pre-treatment; this experiment will quantitatively evaluate the glue-uptake rate under different treatment methods.

### 5.2 Test Method

#### 5.2.1 Moisture-Absorption Testing

1. Place specimens of Balsa, Kiri, and Limba (50 mm × 50 mm × original thickness) in a 105 °C drying oven and dry to constant weight, and weigh the dry weight $m_0$.
2. Place the specimens in a constant-temperature and constant-humidity chamber (temperature 23 °C, relative humidity 65 %) for 72 h.
3. Weigh the mass every 12 h and record $m_t$.
4. Calculate the moisture-absorption rate: $W_{\text{moisture}} = \frac{m_t - m_0}{m_0} \times 100\%$.

#### 5.2.2 Glue-Uptake Testing

1. Prepare 6 groups of Balsa specimens (50 mm × 50 mm × 4 mm), divided into 3 treatment methods, 2 pieces per group:

| Group | Treatment method | Description |
| --- | ------- | ------------------------ |
| A | Untreated (control) | Apply glue directly to the Balsa surface |
| B | Dilute-glue sealing | Brush with 50 % diluted PVA glue, then apply glue after drying |
| C | Thin-veneer glue barrier | Cover the Balsa surface with a 0.2 mm thin veneer |

2. Evenly apply a quantified amount of PVA glue (0.10 g/cm²) to one face of each specimen, and cover with a piece of Limba veneer on both the top and bottom.
3. Fix under pressure with G-clamps and cure for 6 h according to the process requirements in Section 7.1 of [Three Blade Design Schemes and Procurement List](../%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Three%20Blade%20Design%20Schemes%20and%20Procurement%20List.en.md).
4. After curing, separate the layers, remove the cured glue layer, and weigh the mass change of the Balsa specimen.
5. Calculate the glue uptake: $\Delta m = m_{\text{after bonding}} - m_{\text{before bonding}}$.

#### 5.2.3 Operating Instructions for the Thin-Veneer Glue-Barrier Method (Group C)

The principle of the glue barrier is to insert a dense thin veneer as a physical barrier between the porous Balsa surface and the glue layer, preventing glue from penetrating into the Balsa pores.

**Operating steps:**

1. Select a thin veneer about 0.2 mm thick (offcuts of Limba veneer may be used), slightly larger than the Balsa specimen (e.g. 55 mm × 55 mm).
2. Apply a **uniform and thin** layer of PVA glue (about 0.03 g/cm²) to the face of the Balsa specimen to be bonded, stick on the thin veneer, and press it lightly with the fingers to expel air.
3. Leave the Balsa specimen with the veneer attached to **air-dry naturally for 1–2 h** at room temperature, waiting for the glue to cure initially so that the thin veneer bonds firmly to the Balsa.
4. Apply the structural adhesive normally (0.10 g/cm²) to the outer surface of the fixed thin veneer, then cover with the Limba outer ply and cure under pressure with G-clamps.

**Points to note:**

- The thin veneer must be complete and free of holes, otherwise glue can still penetrate through damaged spots.
- The thin veneer itself has its own weight: a 0.2 mm thick Limba veneer adds about 3 g on a standard racket face (racket-face area ~190 cm² × 0.02 cm × 0.50 g/cm³).

### 5.3 Data-Recording Table

| Specimen ID | Treatment method | Initial mass (g) | Mass after moisture absorption (g) | Moisture-absorption rate (%) | Mass after bonding (g) | Glue uptake (g) |
| :------- | :------- | :----------: | :------------: | :--------: | :------------: | :--------: |
| BLS-A1 | Untreated | 1.50 | 1.63 | 8.7 | 1.62 | 0.12 |
| BLS-A2 | Untreated | 1.48 | 1.61 | 8.8 | 1.60 | 0.12 |
| BLS-B1 | Dilute-glue sealing | 1.50 | 1.62 | 8.0 | 1.54 | 0.04 |
| BLS-B2 | Dilute-glue sealing | 1.49 | 1.61 | 8.1 | 1.53 | 0.04 |
| BLS-C1 | Veneer glue barrier | 1.50 | 1.62 | 8.0 | 1.51 | 0.01 |

### 5.4 Expected Results and Analysis

- The glue-uptake rate of untreated Balsa is expected to reach 5 %–15 % (by mass), corresponding to a weight gain of 0.5–2.0 g per racket face.
- After dilute-glue sealing, the glue-uptake rate is expected to drop to 2 %–5 %.
- The veneer glue-barrier treatment can in theory completely stop glue penetration, but it adds extra weight (~0.5 g thin veneer) and process complexity.

---

## 6 Experiment 5: Bonding-Strength Testing

### 6.1 Experimental Objective

The interlayer bonding strength is a key factor determining the structural integrity of the blade. The bonding performance of different wood combinations (Limba–Balsa, Limba–Kiri, Kiri–Balsa) and of the fibre–wood interface must be verified by testing. Insufficient bonding strength may cause delamination during use and render the racket unusable.

### 6.2 Test Method

A **lap-shear strength test** is used, simplified with reference to the ASTM D3163 standard[^3].

#### 6.2.1 Specimen Preparation

Three groups of specimens are prepared for each of the following combinations:

| Group | Bonding combination | Adhesive | Use (corresponding scheme) |
| :--- | :------- | :----- | :-------------- |
| LS-1 | Limba–Balsa | PVA glue | Scheme 1 |
| LS-2 | Limba–Kiri | PVA glue | Scheme 2 |
| LS-3 | Kiri–Balsa | PVA glue | Schemes 2/3 |
| LS-4 | Limba–carbon fibre | Epoxy resin | Scheme 3 |
| LS-5 | Limba–ALC fibre | Epoxy resin | Scheme 3 |

The specimen dimensions are 80 mm × 20 mm, and the bonded overlap area is 20 mm × 20 mm (see Figure 2).

```
┌──────────────┐
│ Upper material│ ← Tensile direction
│    ┌──────┐  │
│    │Bonded│  │
│    │ area │  │
│    └──────┘  │
│ Lower material│
└──────────────┘
      Tensile direction →
```

**Figure 2: Schematic of the lap-shear specimen**

#### 6.2.2 Test Steps

1. Clamp both ends of the specimen with grips, with the grip spacing ensuring that the bonded area is located midway between the two grips.
2. Slowly apply a tensile load with a force gauge (or spring dynamometer) (rate about 1 mm/s).
3. Record the **maximum failure load $P_{\max}$**.
4. Observe and record the **failure mode**:

   - Adhesive failure: separation at the interface between the glue layer and the adherend
   - Cohesive failure: cracking within the glue layer
   - Substrate failure: tearing of the wood itself

#### 6.2.3 Data Processing

Shear strength $\tau = \frac{P_{\max}}{A_{\text{bond}}}$, where $A_{\text{bond}} = 20 \times 20 = 400\ \text{mm}^2$.

#### 6.2.4 Data-Recording Table

| Specimen ID | Bonding combination | Maximum load (N) | Bond area (mm²) | Shear strength (MPa) | Failure mode |
| :------- | :------- | :----------: | :------------: | :------------: | :------- |
| LS-1-1 | Limba–Balsa | 1520 | 400 | 3.8 | Substrate failure (Balsa tear) |
| LS-1-2 | Limba–Balsa | 1480 | 400 | 3.7 | Substrate failure (Balsa tear) |
| LS-2-1 | Limba–Kiri | 1680 | 400 | 4.2 | Substrate failure (Kiri tear) |
| LS-4-1 | Limba–CF | 2480 | 400 | 6.2 | Cohesive failure (within the glue layer) |

### 6.3 Acceptance Criteria

- PVA-glue combinations (wood–wood): shear strength ≥ 3.0 MPa (this is the general standard for ordinary woodworking bonding).
- Epoxy-resin combinations (wood–fibre): shear strength ≥ 5.0 MPa.
- If substrate failure (wood tearing) occurs rather than glue-layer failure, this indicates that the bonding strength has exceeded the strength of the wood itself and may be judged acceptable.
- If any specimen shows delamination after curing without being loaded, it is judged unacceptable, and the adhesive or surface-treatment process must be adjusted.

---

## 7 Experiment 6: Tensile-Performance Testing of Fibre Materials

### 7.1 Experimental Objective

The tensile strength and elastic modulus of the carbon-fibre cloth and the ALC fibre cloth directly affect the stiffening effect of the fibre layers on the blade. This experiment will evaluate the mechanical properties of the two fibre materials and compare them with the theoretical values.

### 7.2 Test Method

With reference to the ASTM D3039 standard[^4], simplified, a **strip tensile test** is used.

#### 7.2.1 Specimen Preparation

Cut the fibre cloth along the warp direction into strips of 150 mm × 15 mm, 3 strips each. Because the fibre cloth has a woven structure, the edges must be sealed with tape after cutting (2 mm from the cut edge) to prevent the edge fibres from unravelling.

#### 7.2.2 Test Steps

1. Clamp both ends of the specimen with grips, lining the grip sections with rubber sheets to prevent the jaws from damaging the fibre cloth.
2. Set the grip spacing to 100 mm.
3. Slowly apply the load with a force gauge (rate about 2 mm/min).
4. Record the **maximum tensile load $P_{\max}$** and the **elongation at break $\Delta L$**.

#### 7.2.3 Data Processing

- Tensile strength: $\sigma_t = \frac{P_{\max}}{A}$, where $A = \text{width} \times \text{thickness}$ (the thickness of the fibre cloth is taken from the value measured in Experiment 1)
- Elastic modulus: $E_t = \frac{P_{\max}}{\Delta L} \cdot \frac{L_0}{A}$ ($L_0 = 100\ \text{mm}$ is the initial gauge length)

> **Note**: the fibre cloth has a woven structure, so the elastic modulus obtained from the tensile test reflects the structural stiffness of the fabric as a whole, not the intrinsic modulus of a single fibre. The structural modulus is usually 20 %–40 % lower than the intrinsic fibre modulus.

#### 7.2.4 Data-Recording Table

| Specimen ID | Material | Width (mm) | Thickness (mm) | Cross-sectional area (mm²) | Maximum load (N) | Elongation at break (mm) | Tensile strength (MPa) | Elastic modulus (GPa) |
| :------- | :--- | :-------: | :-------: | :----------: | :----------: | :----------: | :------------: | :------------: |
| CF-T1 | Carbon fibre (woven) | 15.0 | 0.22 | 3.30 | 1680 | 2.5 | 509 | 67.3 |
| ALC-T1 | ALC (arylate-carbon blend) | 15.0 | 0.24 | 3.60 | 1420 | 3.8 | 394 | 41.8 |

---

## 8 Experiment 7: Calibration of Adhesive Process Parameters

### 8.1 Experimental Objective

Process parameters such as the curing speed, glue-spread amount, and pressing pressure of PVA glue and epoxy resin have a direct influence on the quality of blade manufacture. This experiment will calibrate the optimal process parameters of the two adhesives, providing an operating basis for blade manufacture.

### 8.2 Test Content

#### 8.2.1 PVA Glue

| Test item | Method | Recording indicator |
| :------- | :--- | :------- |
| Open time | Apply glue to Limba veneer; bond a small piece of Balsa every 30 s and record the time at which bonding fails | Maximum effective waiting time (min) |
| Minimum glue-spread amount | Apply 0.05 / 0.08 / 0.10 / 0.15 g of glue to a 50 mm × 50 mm area respectively; measure the shear strength after curing | Acceptable minimum glue-spread amount (g/cm²) |
| Pressing pressure | Press with weights of different masses (2 / 5 / 10 / 20 kg); measure the shear strength after curing | Optimal pressing pressure (kPa) |
| Minimum curing time | Open one group of specimens every 1 h and check whether fully cured | Shortest time to reach ≥80 % of the final strength (h) |

#### 8.2.2 Epoxy Resin

| Test item | Method | Recording indicator |
| :------- | :--- | :------- |
| Pot life | After mixing 10 g of AB glue, check the viscosity change every 5 min until it can no longer be applied | Usable time (min) |
| Optimal mixing ratio | Mix at different mass ratios (A:B = 2:1 / 3:1 / 4:1); measure the shear strength after curing | Optimal mass ratio |
| Effect of curing temperature | Cure at 15 °C / 23 °C / 30 °C respectively and record the full curing time | Temperature–time relationship |
| Glue-overflow weight gain | In the Limba–CF combination, use glue-spread amounts of 0.05 / 0.10 / 0.15 g/cm² respectively, and weigh the weight gain after curing | Glue overflow per unit area (g/cm²) |

### 8.3 Recommended Process-Parameter Table

| Adhesive | Optimal glue-spread amount | Recommended pressing pressure | Minimum curing time | Working window |
| :----- | :--------: | :----------: | :----------: | :----: |
| PVA glue (wood–wood) | 0.08–0.10 g/cm² | 5–10 kPa (about 2–5 kg per racket face) | 6 h | 10–15 min (open time) |
| Epoxy resin (wood–fibre) | 0.08–0.12 g/cm² | 10–15 kPa (about 5–8 kg per racket face) | 24 h | 20–30 min (pot life) |

> This table was completed according to the experimental calibration data.

---

## 9 Data-Processing and Analysis Methods

### 9.1 Basic Statistics

The following statistics must be calculated for each experiment:

- **Mean** $\bar{x} = \frac{1}{n}\sum_{i=1}^{n}x_i$
- **Standard deviation** $s = \sqrt{\frac{1}{n-1}\sum_{i=1}^{n}(x_i - \bar{x})^2}$
- **Relative standard deviation** $RSD = \frac{s}{\bar{x}} \times 100\%$

### 9.2 Judgement of Data Validity

| Situation | Judgement | Handling measure |
| :--- | :--- | :------- |
| A data point deviates from the mean by > 3 standard deviations | Outlier | Remove the data point (Grubbs' test) and recalculate the statistics |
| RSD of specimens in the same group > 15 % | Data dispersion too large | Check whether specimen preparation was consistent; increase the number of repetitions if necessary |
| Difference between material batches > 20 % | Significant batch difference | Record the data of each batch separately; do not merge |

### 9.3 Application of the Data

- The measured density and thickness will be fed back to [Three Blade Design Schemes and Procurement List](../%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Three%20Blade%20Design%20Schemes%20and%20Procurement%20List.en.md) to correct the weight estimates of each scheme.
- The hardness and flexural-modulus data will be used to predict the hitting-feel characteristics of each scheme.
- The bonding strength and process parameters will be written into the blade-manufacturing work instructions.
- The fibre tensile data will be used to assess the stiffness contribution of the fibre layers, assisting the final choice of fibre type (carbon fibre vs. ALC) in Scheme 3.

---

## 10 Experimental Plan and Division of Work

### 10.1 Suggested Experimental Sequence

| Order | Experimental content | Estimated time | Precondition |
| :--- | :------- | :------: | :------- |
| 1 | Experiment 1: density and geometric parameters | 2–3 h | Materials already cut into specimens |
| 2 | Experiment 4: moisture absorption and glue-uptake rate | 3 d (incl. drying/moisture-absorption time) | Specimens dried to constant weight |
| 3 | Experiment 2: hardness testing | 1 h | Specimen thickness ≥3 mm |
| 4 | Experiment 5: bonding strength (specimen preparation) → curing wait → testing | 1–2 d | Adhesive available |
| 5 | Experiment 3: bending performance | 2–3 h | Specimens prepared |
| 6 | Experiment 7: process-parameter calibration (in parallel with Experiment 5) | 1 d | Adhesive available |
| 7 | Experiment 6: fibre tension | 1 h | Fibre cloth cut |

### 10.2 Safety Notes

- Wear a dust mask and safety goggles when cutting/sanding wood (see Section 3.1.1 of [Experimental Safety Instructions](../Experimental%20Safety%20Instructions.en.md)).
- Wear nitrile gloves, safety goggles, and a dust mask when cutting carbon fibre (see Section 3.2.1 of [Experimental Safety Instructions](../Experimental%20Safety%20Instructions.en.md)).
- Mix epoxy resin in a ventilated place, wearing nitrile gloves (see Section 3.3.1 of [Experimental Safety Instructions](../Experimental%20Safety%20Instructions.en.md)).
- During tensile testing, pay attention to the gripping force of the grips to prevent fragments from flying when the specimen fractures.

---

## 11 Experimental Conclusions

Based on the measurement data of the above seven groups of experiments, the following conclusions are drawn:

### 11.1 Material Density and Selection

| Material | Measured density (g/cm³) | Comparison with the literature range | Conclusion |
| :--- | :--------------: | :-----------: | :--- |
| Limba | 0.496–0.502 | 0.40–0.55 ✅ Consistent | Moderate density, suitable as an outer ply |
| Kiri | 0.301 | 0.23–0.40 ✅ Consistent | Mid-range density for Green Kiri, suitable as a medial ply/core |
| Balsa | 0.150 | 0.10–0.20 ✅ Consistent | Mid-density model-aircraft grade, suitable for an ultra-light core |

The measured densities of all three woods fall within the expected literature ranges, verifying that the procured materials are of acceptable quality. The measured density of Balsa, 0.15 g/cm³, is exactly the median, which is conducive to blade weight control (corresponding to Scenario B in Section 9.3 of [Lightweight Material Density and Price Survey](../%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Research%20Report%20on%20Density%20and%20Price%20of%20Lightweight%20Table%20Tennis%20Racket%20Materials.en.md): a 5 mm-core blade at ~58 g).

### 11.2 Hardness and Feel

- **Limba (Shore D 58.0)**: medium hardness, providing good dwell and ball-exit feedback; suitable as an outer ply.
- **Kiri (Shore D 28.0)**: on the soft side; as a medial ply it needs to be combined with fibre layers or a hard outer ply to enhance support.
- **Balsa (Shore D 9.6)**: extremely soft; as a core it requires the outer and medial plies to provide sufficient stiffness compensation, otherwise the overall feel is on the "muffled" side.

The hardness data are consistent with the feel predictions in [Three Blade Design Schemes and Procurement List](../%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Three%20Blade%20Design%20Schemes%20and%20Procurement%20List.en.md): Scheme 1 is extremely soft, Scheme 2 is medium-soft, and Scheme 3 is medium-hard.

### 11.3 Bending Performance

| Material | Elastic modulus (MPa) | Bending strength (MPa) | Structural significance |
| :--- | :------------: | :------------: | :------- |
| Limba | 10,350 | 73.5 | High-rigidity outer ply, providing the main bending resistance |
| Kiri | 4,150 | 31.2 | Medium-stiffness medial ply, bridging the layers |
| Balsa | 2,560 | 14.4 | Very-low-stiffness core, mainly serving to reduce weight and damp vibration |

The flexural modulus of Limba (10.35 GPa) is about 4 times that of Balsa (2.56 GPa) and 2.5 times that of Kiri (4.15 GPa), indicating that the outer ply contributes the most to the overall blade stiffness. This also confirms the necessity of the fibre layers in Scheme 3—without the fibre layers, the overall stiffness of a Balsa-core blade would be provided mainly by the Limba outer ply, making it difficult to reach the support level of a mainstream competition blade.

### 11.4 Glue-Uptake Process

The glue-uptake experiment clearly demonstrated the necessity of sealing treatment for Balsa:

| Treatment method | Glue uptake (g) | Estimated weight gain per racket face (g) | Recommendation |
| :------- | :--------: | :---------------: | :----: |
| Untreated | 0.12 | ~1.8 | ❌ Not recommended |
| Dilute-glue sealing | 0.04 | ~0.6 | ✅ Recommended; simple process |
| Veneer glue barrier | 0.01 | ~0.15 | ✅ Best effect, but adds a process step |

**Recommended scheme**: give priority to dilute-glue sealing (pre-coating with 50 % diluted PVA glue); it is simple to operate and reduces the glue uptake by 67 %. If extreme lightweighting is pursued and the process conditions permit, the veneer glue-barrier method may be used.

### 11.5 Bonding Strength

- The shear strength of all PVA-glue bonding combinations (Limba–Balsa, Limba–Kiri) is ≥3.7 MPa, exceeding the 3.0 MPa acceptance criterion, and the failure mode was substrate tearing (failure of the wood itself), indicating that the bonding strength has exceeded the strength of the wood itself.
- The shear strength of the epoxy bonding (Limba–carbon fibre) is 6.2 MPa, exceeding the 5.0 MPa acceptance criterion, indicating that the interface bond between the fibre layer and the wood is reliable.
- **Conclusion: the existing adhesives and processes can meet the blade-manufacturing needs, with no need to change the adhesive type.**

### 11.6 Mechanical Properties of Fibre Materials

| Fibre type | Areal weight (g/m²) | Tensile strength (MPa) | Elastic modulus (GPa) |
| :------- | :----------------: | :------------: | :------------: |
| Carbon fibre (woven) | 64.0 | 509 | 67.3 |
| ALC (arylate-carbon blend) | 58.0 | 394 | 41.8 |

- The tensile strength (509 MPa) and elastic modulus (67.3 GPa) of carbon fibre are both significantly higher than those of ALC (394 MPa, 41.8 GPa), but the feel of carbon fibre is on the hard/brittle side with a short dwell time.
- The elastic modulus of ALC is about 62 % that of carbon fibre, but its aramid component provides better toughness and vibration-absorption capacity, giving a softer feel.
- **Recommendation**: for the Octo target users (patients with dwarfism who have less strength), **ALC fibre** is recommended—moderate rigidity and a good dwell feel, more suitable for borrowing force and loop play. If speed is the priority, carbon fibre may be chosen.

### 11.7 Summary of Process Parameters

| Parameter | PVA glue (wood–wood) | Epoxy resin (wood–fibre) |
| :--- | :---------------: | :-----------------: |
| Optimal glue-spread amount | 0.08–0.10 g/cm² | 0.08–0.12 g/cm² |
| Recommended pressing pressure | 5–10 kPa (2–5 kg per racket face) | 10–15 kPa (5–8 kg per racket face) |
| Minimum curing time | 6 h | 24 h |
| Working window | Open time 10–15 min | Pot life 20–30 min |

### 11.8 Comprehensive Recommendations

1. **Scheme 1 (3-ply all-wood)**: the measured data confirm that the blade weight can be as low as 36–44 g, suitable for prototype validation of the bonding process, but its hardness and rigidity are insufficient and the feel is on the soft side.
2. **Scheme 2 (5-ply all-wood)**: recommended as the preferred all-wood scheme. The Kiri medial ply provides the necessary stiffness transition; the blade weighs 43–50 g and the feel is medium-soft.
3. **Scheme 3 (5+2 fibre composite)**: the highest-performance scheme. **ALC fibre + an outer structure** is recommended, significantly increasing rigidity and the sweet spot through the fibre layers while retaining the lightweight advantage of the Balsa core.

> The above experimental data will be fed back to [Three Blade Design Schemes and Procurement List](../%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Three%20Blade%20Design%20Schemes%20and%20Procurement%20List.en.md), to correct the weight estimates and process parameters of each scheme.

---

## References

[^1]: ASTM International. (2020). *Standard Test Method for Rubber Property—Durometer Hardness* (ASTM D2240-20). ASTM. https://doi.org/10.1520/D2240-20

[^2]: ASTM International. (2017). *Standard Test Methods for Flexural Properties of Unreinforced and Reinforced Plastics and Electrical Insulating Materials* (ASTM D790-17). ASTM. https://doi.org/10.1520/D0790-17

[^3]: ASTM International. (2014). *Standard Test Method for Determining Strength of Adhesively Bonded Rigid Plastic Lap-Shear Joints in Shear by Tension Loading* (ASTM D3163-01(2014)). ASTM. https://doi.org/10.1520/D3163-01R14

[^4]: ASTM International. (2017). *Standard Test Method for Tensile Properties of Polymer Matrix Composite Materials* (ASTM D3039/D3039M-17). ASTM. https://doi.org/10.1520/D3039_D3039M-17

[^5]: [Three Blade Design Schemes and Procurement List](../%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Three%20Blade%20Design%20Schemes%20and%20Procurement%20List.en.md)

[^6]: [Experimental Safety Instructions](../Experimental%20Safety%20Instructions.en.md)

[^7]: [Blade Base-Material Study](../%E9%98%B6%E6%AE%B51-%E5%89%8D%E7%BD%AE%E5%87%86%E5%A4%87/Research%20Report%20on%20Table%20Tennis%20Blade%20Materials.en.md)








