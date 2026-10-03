# Octo Table Tennis Racket Final Design

## 1 Design Overview

### 1.1 Project Background

The Octo (Octopus) table tennis racket project aims to design a customised lightweight table
tennis racket for **patients with dwarfism (achondroplasia)**. The target users' hand size
(palm width 6.0–8.0 cm, palm length 6–9 cm) and arm span (110–122 cm) are all markedly smaller
than those of the general population, and standard finished rackets (170–200 g) cannot be
controlled effectively by them. This scheme integrates all research results from
[Hand-Size and Grip-Strength Study of Dwarfism Patients](./%E9%98%B6%E6%AE%B51-%E5%89%8D%E7%BD%AE%E5%87%86%E5%A4%87/Research%20Report%20on%20Hand-Size%20and%20Grip-Strength%20of%20Dwarfism%20Patients.en.md),
[Standard Racket Technical Baseline](./%E9%98%B6%E6%AE%B51-%E5%89%8D%E7%BD%AE%E5%87%86%E5%A4%87/Standard%20Table%20Tennis%20Racket%20Technical%20Parameter%20Baseline%20Report.en.md),
[Lightweight Material Density and Price Survey](./%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Research%20Report%20on%20Density%20and%20Price%20of%20Lightweight%20Table%20Tennis%20Racket%20Materials.en.md),
[Blade Base-Material Study](./%E9%98%B6%E6%AE%B51-%E5%89%8D%E7%BD%AE%E5%87%86%E5%A4%87/Research%20Report%20on%20Table%20Tennis%20Blade%20Materials.en.md),
[Three Blade Design Schemes and Procurement List](./%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Three%20Blade%20Design%20Schemes%20and%20Procurement%20List.en.md),
[Slim-Handle and Adjustable Handle Design Report](./%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Design%20Report%20on%20Slim-Handle%20and%20Adjustable%20Counterweight%20and%20Length%20Handles.en.md) and
[Wood and Fiber Material Performance Test Report](./%E9%98%B6%E6%AE%B53-%E5%AE%9E%E9%AA%8C%E4%B8%8E%E6%B5%8B%E8%AF%95/Phase-3%20Experiment%20Report%20on%20Performance%20Testing%20of%20Wood%20and%20Fibre%20Materials.en.md), forming
the final definitive design scheme.

### 1.2 Core Design Objectives

| Parameter | Octo target | Standard racket baseline | Change | Design driver |
| :--- | :-------: | :----------: | :------: | :----------- |
| Total weight of finished racket | **110–130 g** | 170–200 g | **−30 % to −40 %** | Reduce joint load, suit grip strength |
| Blade weight | **55–70 g** | 82–95 g | **−25 % to −35 %** | Core weight-reduction objective |
| Handle circumference | **65–80 mm** | 85–95 mm | **−15 % to −25 %** | Palm width 6.0–8.0 cm |
| Handle length | **60–75 mm** | 100 mm | **−25 % to −40 %** | Palm length 6–9 cm |
| Centre-of-gravity position | **Towards the handle (>52 % of total length)** | 46 %–50 % of total length | **Marked rearward shift** | Short arm span → low moment-of-inertia requirement |
| Blade thickness | **5.0–5.6 mm** | 5.5–7.0 mm | −10 % to −20 % | Reduce weight, maintain flexibility |

---

## 2 User Requirements and Ergonomic Inputs

### 2.1 Target-User Hand Size

According to [Hand-Size and Grip-Strength Study of Dwarfism Patients](./%E9%98%B6%E6%AE%B51-%E5%89%8D%E7%BD%AE%E5%87%86%E5%A4%87/Research%20Report%20on%20Hand-Size%20and%20Grip-Strength%20of%20Dwarfism%20Patients.en.md), the hand-size ranges of patients with achondroplasia are as follows:

| Parameter | Adult male | Adult female | Basis for design value |
| :--- | :------: | :------: | :----------- |
| Palm width (cm) | 6.5–8.0 | 6.0–7.5 | Determines the upper limit of handle circumference (65–80 mm) |
| Palm length (cm) | 7–9 | 6–8 | Determines the upper limit of handle length (60–75 mm) |
| Middle-finger length (cm) | 5–6.5 | 4.5–5.5 | Constrains the cross-sectional height of the handle |
| Grip-strength characteristics | Relatively preserved | Relatively preserved | Weight reduction derives more from joint protection |
| Arm span (cm) | ~122 | ~110 | The racket's moment of inertia must be markedly reduced |

### 2.2 Ergonomic Derivation of Handle Geometry

Upper limit of handle circumference (palm width $W$ = 65–80 mm):

$$C_{\text{max}} \approx 0.85 \times W \times \pi = 65\text{–}80\ \text{mm}$$

Upper limit of handle length (palm length $L_{\text{palm}}$ = 70–90 mm):

$$L_{\text{handle}} \leq 0.85 \times L_{\text{palm}} = 60\text{–}75\ \text{mm}$$

---

## 3 Final Structural Design Scheme

### 3.1 Recommended Scheme: 5+2 Fibre Composite Structure

Based on the measured data from the Phase-3 experiments, all three schemes are feasible, but
**Scheme 3 (5+2 external ALC fibre structure) is recommended as the final design scheme**. This
scheme achieves the best balance between lightweight construction and hitting performance: the
fibre layers compensate for the insufficient stiffness of the Balsa core while keeping the total
weight controllable.

#### 3.1.1 Structural Layers (from outside to inside)

```
┌──────────────────────────────────┐
│  ① Limba outer ply    0.50 mm    │  ← measured density 0.50 g/cm³, Shore D 57.8
├──────────────────────────────────┤
│  ② ★ ALC fibre layer  0.24 mm    │  ← measured GSM 58.3 g/m², tensile strength 388 MPa
├──────────────────────────────────┤
│  ③ Kiri medial ply    0.60 mm    │  ← measured density 0.30 g/cm³, elastic modulus 4.15 GPa
├──────────────────────────────────┤
│  ④ Balsa core         3.00 mm    │  ← measured density 0.15 g/cm³, pre-coated with dilute-glue seal
├──────────────────────────────────┤
│  ③ Kiri medial ply    0.60 mm    │
├──────────────────────────────────┤
│  ② ★ ALC fibre layer  0.24 mm    │
├──────────────────────────────────┤
│  ① Limba outer ply    0.50 mm    │
└──────────────────────────────────┘
        Total thickness: 5.68 mm
        ITTF compliance: ✅ wood proportion >85 %
```

#### 3.1.2 Weight Budget Corrected with Measured Densities

Based on the measured data from [Wood and Fiber Material Performance Test Report](./%E9%98%B6%E6%AE%B53-%E5%AE%9E%E9%AA%8C%E4%B8%8E%E6%B5%8B%E8%AF%95/Phase-3%20Experiment%20Report%20on%20Performance%20Testing%20of%20Wood%20and%20Fibre%20Materials.en.md), a precise weight budget is calculated (standard racket-face area 190 cm²):

| Layer | Material | Thickness (mm) | Density/GSM | Plies | Areal weight (g) | Formula |
| :--- | :--- | :-------: | :------: | :--: | :----------: | :------- |
| ① Outer ply | Limba (ρ = 0.498 g/cm³) | 0.50 | 0.498 g/cm³ | 2 | 9.5 | (0.050 × 0.498 × 190) × 2 |
| ② Fibre layer | ALC (GSM 58.3) | 0.24 | 58.3 g/m² | 2 | 2.2 | (58.3 × 0.019) × 2 |
| ③ Medial ply | Kiri (ρ = 0.299 g/cm³) | 0.60 | 0.299 g/cm³ | 2 | 6.8 | (0.060 × 0.299 × 190) × 2 |
| ④ Core | Balsa (ρ = 0.150 g/cm³) | 3.00 | 0.150 g/cm³ | 1 | 8.6 | 0.300 × 0.150 × 190 |
| Glue | Epoxy resin + PVA glue | — | — | 6 layers | 3.5–4.5 | Measured calibration (incl. Balsa glue uptake) |
| **Racket-face subtotal** | | **5.68** | | **7 layers** | **30.6–31.6** | |

**Complete blade total weight**:

| Component | Weight (g) |
| :--- | :------: |
| Bare racket face (incl. glue) | 30.6–31.6 |
| Handle (advanced scheme size M, Balsa + cork covering) | 13–15 |
| Handle screw interface | 1.5 |
| Counterweight-chamber structure | 2 |
| Surface coating (2–3 coats of polyurethane) | 2–3 |
| **Blade total weight (excluding counterweight rod)** | **49–53** |
| Counterweight rod W1 (brass, Φ8 × 25 mm) | 9 |
| **Blade total weight (including counterweight)** | **58–62** |

> **Experimental verification**: the data in Section 9.3 of the test report confirm that the above weight budget is consistent with the measured densities, with a correction of only 1–2 g upward, which does not affect the feasibility of the scheme.

#### 3.1.3 Finished-Racket Total-Weight Budget

| Component | Weight (g) | Remarks |
| :--- | :------: | :--- |
| Blade (incl. counterweight) | 58–62 | Within the 55–70 g target |
| Forehand rubber | 36 | Lightweight rubber, 1.5 mm sponge |
| Backhand rubber | 36 | Lightweight rubber, 1.5 mm sponge |
| Glue (rubber bonding) | 3 | |
| **Total weight of finished racket** | **133–137** | Close to the upper target limit (110–130 g) |

**Room for weight optimisation**:

- To keep strictly within 130 g, the counterweight rod may be removed (W0 cork plug), reducing
  the finished racket to **124–128 g**.
- Alternatively, an ultra-light scheme may be adopted: the Scheme-1 structure (3-ply all-wood,
  no fibre), reducing the finished racket to **111–119 g**.

---

## 4 Final Recommendation of the Three Schemes

| Scheme | Structure | Total thickness | Blade weight (g) | Finished weight (g) | Hardness | Speed | Recommended use |
| :--- | :--- | :---: | :--------: | :--------: | :--: | :--: | :------- |
| **Scheme 1** (conservative) | 3-ply all-wood (Limba + Balsa + Limba) | 5.10 | 37–45 | 111–119 | Very soft | Slow–medium | **Prototype validation**: verify the bonding process and make an initial assessment of feel |
| **Scheme 2** (advanced) | 5-ply all-wood (Limba + Kiri + Balsa + Kiri + Limba) | 5.60 | 44–51 | 118–125 | Medium-soft | Medium | **Main all-wood scheme**: best balance between performance and fabrication difficulty |
| **Scheme 3** (aggressive) | **5+2 fibre composite (Limba + ALC + Kiri + Balsa + Kiri + ALC + Limba)** | **5.68** | **45–52** | **119–126** | **Medium** | **Fast** | **⭐ Recommended final scheme**: the ultimate choice for performance |

**Recommended execution route**:

1. First fabricate **Scheme 1** (3-ply all-wood) to confirm that the bonding process is feasible.
2. Fabricate **Scheme 3** (5+2 ALC fibre) as the final performance scheme.
3. Scheme 2 serves as the fallback—if Scheme 3 encounters fabrication difficulties, revert to
   Scheme 2.

---

## 5 Material Selection and Experimental Verification Basis

### 5.1 Outer Ply: Limba

| Parameter | Measured value | Literature range | Experimental basis |
| :--- | :----: | :------: | :------- |
| Density | 0.498 g/cm³ | 0.40–0.55 | Experiment 1 ✅ |
| Shore D hardness | 57.8 | 50–65 | Experiment 2 ✅ |
| Elastic modulus | 10.27 GPa | 8–12 GPa | Experiment 3 ✅ |
| Bending strength | 73.2 MPa | 60–90 MPa | Experiment 3 ✅ |
| Bonding shear strength (Limba–Balsa) | 3.75 MPa | ≥3.0 MPa (acceptable) | Experiment 5 ✅ |

**Reason for selection**: Limba provides the hardness (Shore D 57.8) and elastic modulus
(10.27 GPa) required of the outer ply, and is the principal contributor to bending resistance in
the three-layer structure. Its flexural modulus is 4 times that of Balsa and 2.5 times that of
Kiri, ensuring the basic rigid support of the blade.

### 5.2 Medial Ply: Kiri

| Parameter | Measured value | Literature range | Experimental basis |
| :--- | :----: | :------: | :------- |
| Density | 0.299 g/cm³ | 0.23–0.40 | Experiment 1 ✅ |
| Shore D hardness | 28.0 | 20–35 | Experiment 2 ✅ |
| Elastic modulus | 4.15 GPa | 3–6 GPa | Experiment 3 ✅ |
| Bending strength | 31.2 MPa | 25–45 MPa | Experiment 3 ✅ |

**Reason for selection**: Kiri's density (0.299 g/cm³) is only 60 % that of Limba, and its elastic
modulus (4.15 GPa) lies between that of Limba (10.27 GPa) and Balsa (2.53 GPa), giving an ideal
stiffness transition. As a medial ply, it raises the overall stiffness of the blade without
significantly increasing weight.

### 5.3 Core: Balsa

| Parameter | Measured value | Literature range | Experimental basis |
| :--- | :----: | :------: | :------- |
| Density | 0.150 g/cm³ | 0.10–0.20 | Experiment 1 ✅ |
| Shore D hardness | 9.5 | 5–15 | Experiment 2 ✅ |
| Elastic modulus | 2.53 GPa | 2–5 GPa | Experiment 3 ✅ |
| Moisture-absorption rate | 8.7 % | — | Experiment 4 |
| Glue uptake after dilute-glue sealing | 0.04 g (67 % reduction) | — | Experiment 4 ✅ recommended |

**Reason for selection**: Balsa is the core weight-control layer—its density is only
0.15 g/cm³, contributing approximately 8.6 g at a thickness of 3 mm. Note however:

- **Dilute-glue sealing pre-treatment** is mandatory (pre-coating with 50 % diluted PVA glue),
  which reduces the glue-uptake rate by 67 %.
- Balsa has a high moisture-absorption rate (8.7 %); the blade must be sealed with a surface
  coating immediately after fabrication.

### 5.4 Fibre Layer: ALC Arylate-Carbon Blend (recommended)

| Parameter | Measured value | Carbon-fibre comparison | Experimental basis |
| :--- | :----: | :--------: | :------- |
| Areal weight | 58.3 g/m² | 63.7 g/m² (heavier) | Experiment 1 ✅ |
| Tensile strength | 388 MPa | 516 MPa (higher) | Experiment 6 ✅ |
| Elastic modulus | 41.3 GPa | 67.2 GPa (higher) | Experiment 6 ✅ |
| Elongation at break | 3.8 % | 2.5 % (more brittle) | Experiment 6 ✅ better toughness |
| Wood–fibre bonding strength | 5.90 MPa | 6.18 MPa | Experiment 5 ✅ |

**Reason for recommendation**: for target users with less strength, ALC is more suitable than
carbon fibre—its elongation at break is 52 % higher (longer dwell time, softer feel), and its
areal weight is lighter (8.5 % lower). If subsequent tests find that the ALC scheme's ball-exit
speed is insufficient, it may be switched to carbon fibre.

### 5.5 Adhesives

| Use | Adhesive type | Process parameters | Experimental basis |
| :--- | :--- | :------- | :------- |
| Wood–wood (Limba/Kiri/Balsa) | PVA glue | Spread 0.08–0.10 g/cm², pressure 2.5–5 kPa, cure ≥6 h | Experiment 7 ✅ |
| Wood–fibre (Limba–ALC) | Epoxy resin (AB glue) | Mix ratio A:B = 3:1, spread 0.08–0.12 g/cm², pressure 5–10 kPa, cure ≥24 h (23 °C) | Experiment 7 ✅ |
| Balsa sealing pre-treatment | PVA glue (50 % diluted) | Pre-coat and air-dry before lamination | Experiment 4 ✅ |

**Key conclusion**: Experiment 5 verified that the shear strength of all bonding combinations
exceeds the acceptance criterion. The failure mode of the PVA-glue group was substrate tearing
(failure of the wood itself) and that of the epoxy group was cohesive failure—both indicate that
the bonding-interface strength is fully adequate.

---

## 6 Handle Design

### 6.1 Recommended Scheme: Advanced Scheme (Interchangeable Handle + Counterweight Chamber)

Based on the comprehensive analysis of [Slim-Handle and Adjustable Handle Design Report](./%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Design%20Report%20on%20Slim-Handle%20and%20Adjustable%20Counterweight%20and%20Length%20Handles.en.md), the **advanced scheme**—a modular interchangeable handle plus a built-in counterweight chamber in the handle—is recommended as the final scheme.

| Component | Specification | Design basis |
| :--- | :--- | :------- |
| Handle type | Scheme B: two-piece interchangeable handle | Modular interface (M3 × 2 screws + 2 locating pins) |
| Length options | S (60 mm) / M (68 mm) / L (75 mm) | Covers palm length 6–9 cm (ergonomic derivation) |
| Circumference options | S (65 mm) / M (72 mm) / L (80 mm) | Covers palm width 6.0–8.0 cm |
| Cross-sectional shape | Elliptical (reduced-size FL) | Balances forehand/backhand switching smoothness |
| Handle-body material | Balsa (lightweight) + Ayous interface end | Densities verified in Experiment 1: Balsa 0.15, Ayous 0.35 g/cm³ |
| Surface covering | Cork sheet (1.5 mm) | Friction coefficient 0.40–0.55, anti-slip and sweat-absorbing |
| Counterweight method | Scheme F: counterweight chamber at the handle end (Φ8 × 25 mm) | M10 threaded cap, interchangeable counterweight rods |

### 6.2 Counterweight-Rod Specifications

| Model | Material | Weight | CG effect (distance from racket top) | CG percentage | Recommended use |
| :--- | :--- | :--: | :---------------: | :--------: | :------- |
| W0 | Cork (empty) | ~1 g | ~109 mm | 48.2 % | Lightest configuration, close to standard CG |
| W1 | Brass | ~9 g | ~126 mm | **55.5 %** | ⭐ **Recommended**: effectively shifts the CG rearward |
| W2 | Stainless steel | ~8 g | ~124 mm | 54.8 % | Alternative, slightly lighter than brass |
| W3 | Lead (encapsulated and sealed) | ~12 g | ~131 mm | 57.5 % | Extreme rearward CG shift (observe safety precautions) |

### 6.3 Verification of the Centre-of-Gravity Calculation

Calculated for the typical configuration of the advanced scheme:

| Component | Mass (g) | CG distance from racket top (mm) | Moment (g·mm) |
| :--- | :------: | :-------------: | :---------: |
| Bare racket face | 31.6 | 78.5 | 2,481 |
| Handle + counterweight chamber | 14.5 | 192.5 | 2,791 |
| Counterweight W1 (brass) | 9.0 | 222.5 | 2,003 |
| **Total** | **55.1** | — | **7,275** |

Overall CG position:

$$x_{\text{CG}} = \frac{7,275}{55.1} = 132.1\ \text{mm}$$

Total racket length $L_{\text{total}} = 157 + 68 = 225\ \text{mm}$:

$$\frac{132.1}{225} = 58.7\ \% \text{ (from the racket top)}$$

**Conclusion**: after counterweighting, the CG lies at 58.7 % of the total length, markedly
biased towards the handle, far lower than the moment of inertia of a standard shakehand racket
(46 %–50 %).

---

## 7 Recommended Rubber Configuration

Based on the survey data from [Lightweight Material Density and Price Survey](./%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Research%20Report%20on%20Density%20and%20Price%20of%20Lightweight%20Table%20Tennis%20Racket%20Materials.en.md):

| Scheme | Forehand rubber | Backhand rubber | Weight per side (g) | Both sides + glue (g) | Total price (CNY) |
| :--- | :------- | :------- | :--------: | :-----------: | :------: |
| **Ultra-light** (recommended) | 729 FX SuperSoft 1.5 mm | LKT Pro XT 1.5 mm | 36 | 75 | 80–120 |
| Economical light | 729-40S 2.0 mm | LKT Pro XP 1.8 mm | 40 | 83 | 60–100 |
| Balanced scheme | 729-5 2.0 mm / Nittaku Fastarc G-1 | Same or similar | 44 | 92 | 100–300 |

> **Recommendation**: give preference to the ultra-light scheme (total rubber weight 75 g) to preserve more weight margin for the blade.

---

## 8 Manufacturing Process Specification

### 8.1 Process Flow

```
Step 1: Balsa sealing pre-treatment
  └ Evenly brush 50 % diluted PVA glue onto both faces of the Balsa core → air-dry at room temperature ≥4 h
  └ Basis: Experiment 4 glue-uptake test → glue uptake reduced by 67 %

Step 2: Cutting of materials
  └ Limba outer ply: sharp utility knife + straightedge, cut along the grain to 157×150 mm
  └ Kiri medial ply: cut to the corresponding size, thickness 0.6 mm
  └ Balsa core: cut to the corresponding size, thickness 3.0 mm
  └ ALC fibre cloth: cut with scissors, apply tape on both sides of the cut line to reduce fraying
  └ Note: wear a dust mask and safety goggles

Step 3: Interlayer glue application
  └ Wood–wood: PVA glue, spread 0.08–0.10 g/cm² (calibrated in Experiment 7)
  └ Wood–fibre: epoxy resin A:B = 3:1, spread 0.08–0.12 g/cm²
  └ Working window: PVA glue ≤12 min, epoxy resin 20–25 min (23 °C)
  └ Align and press each layer immediately after coating

Step 4: Pressing and curing
  └ PVA-glue layers (all-wood schemes): pressure 2.5–5 kPa (≈5–10 kg per racket face), ≥6 h
  └ Epoxy layers (fibre schemes): pressure 5–10 kPa (≈10–20 kg per racket face), ≥24 h
  └ Note: a pressure >10 kPa may crush the Balsa (key limitation!)
  └ Place wooden blocks/rubber sheets between the wood and the clamps to prevent indentation

Step 5: Shaping and sanding
  └ Coarse sanding: sandpaper #80–#120 → shaping
  └ Fine sanding: sandpaper #240–#400 → smooth surface
  └ Round the edges with R2–3 mm fillets to improve grip comfort

Step 6: Handle fabrication
  └ Method A (one-piece): direct sanding to shape × 1
  └ Method B (interchangeable handle): CNC/hand-made S/M/L three-stage modules
  └ Counterweight chamber: drill a Φ8 mm blind hole with a drill press, depth 25 mm, tapped with an M10×1 tap

Step 7: Surface finishing
  └ 2–3 coats of polyurethane varnish, each coat thin, with light sanding using #600 sandpaper in between
  └ Handle area: cork sheet (1.5 mm) + woodworking glue

Step 8: Counterweighting and assembly
  └ Screw in counterweight rod W1 (brass, recommended), or W0 (no counterweight)
  └ Modular handle: fastened with M3 screws (torque 0.5–0.8 N·m)
  └ Attach the rubbers → leave to cure ≥24 h

Step 9: Quality inspection
  └ Weighing: blade weight 58–62 g (incl. counterweight), finished-racket total weight 133–137 g
  └ Thickness: caliper check of total thickness 5.68 ± 0.15 mm
  └ CG: balance point 130–135 mm from the racket top (58 %–60 % of the total length)
  └ Appearance: layer-alignment deviation ≤0.5 mm, no glue overflow
```

### 8.2 Summary of Safety Precautions

| Process | Protective equipment | Reference |
| :--- | :------- | :--- |
| Wood cutting/sanding | N95 dust mask + safety goggles + cut-resistant gloves | [Experimental Safety Instructions](./Experimental%20Safety%20Instructions.en.md) 3.1.1 / 3.1.2 |
| Carbon-fibre/ALC cutting | Safety goggles + dust mask + long-sleeved work clothes | Experimental Safety Instructions 3.2.1 |
| Epoxy mixing | Nitrile gloves + ventilated environment | Experimental Safety Instructions 3.3.1 |
| Counterweight fabrication (metal) | Safety goggles + dust mask (if sanding is involved) | Experimental Safety Instructions 2.2 |

---

## 9 Expected Performance Indicators

### 9.1 Physical-Performance Prediction

| Indicator | Predicted value | Comparison with standard racket | Basis |
| :--- | :----: | :----------: | :---- |
| Blade weight | 58–62 g (incl. counterweight) | 82–95 g (−35 %) | Measured-density-corrected budget |
| Finished-racket total weight | 133–137 g (incl. rubbers) | 170–200 g (−30 %) | Measured-density-corrected budget |
| CG position | 58 %–60 % of total length from the racket top | 46 %–50 % (marked rearward shift) | Calculation in §7 of the slim-handle report |
| Blade thickness | 5.68 mm | 5.5–7.0 mm (moderate) | Scheme-3 structural design |
| Handle length | 60–75 mm (three interchangeable options) | 100 mm (−25 % to −40 %) | Ergonomic derivation |

### 9.2 Feel Prediction

| Item | Prediction | Explanation |
| :--- | :--- | :--- |
| Hardness | **Medium** | External ALC fibre (41.3 GPa) provides moderate stiffness; the Limba outer ply (Shore D 57.8) gives a soft touch |
| Dwell feel | **Good** | The ALC fibre has an elongation at break of 3.8 %, giving a longer dwell time than an all-carbon-fibre scheme |
| Ball-exit speed | **Fast** | The ALC fibre layer provides elastic acceleration; the external structure responds even to small forces |
| Sweet spot | **Large** | The fibre layers enlarge the effective hitting area |
| Vibration damping | **Excellent** | The Balsa core (9.5 Shore D) provides excellent vibration absorption |

### 9.3 Expected Subjective Feel

- **Control**: with the CG shifted rearward to 58 %–60 % of the total length, the moment of
  inertia is markedly reduced and the swing is agile, suitable for users with a short arm span.
- **Power feedback**: the ALC fibre layer gives a clear sense of acceleration when force is
  applied, and performs well when borrowing force with light effort.
- **Dwell feel**: the ALC + Balsa blade combination provides a medium-to-slightly-long dwell
  time, conducive to generating loops.
- **Grip comfort**: the elliptical cross-section + cork covering (friction coefficient
  0.40–0.55) is anti-slip and sweat-absorbing, suited to a palm width of 6–8 cm.

---

## 10 Cost Budget

### 10.1 Material Cost

| Category | Item | Quantity | Unit price (CNY) | Subtotal (CNY) |
| :--- | :--- | :-: | :------: | :-------: |
| Wood | Limba veneer (0.5 mm) | 3 sheets | 10–25 | 30–75 |
| | Kiri board (3–4 mm) | 1 piece | 20–50 | 20–50 |
| | Balsa board (4–6 mm) | 2 pieces | 15–40 | 30–80 |
| Fibre | ALC fibre cloth | 1 sheet | 80–200 | 80–200 |
| Handle | Balsa strip (30×30×100 mm) | 2 strips | 5–10 | 10–20 |
| | Cork sheet (1.5–2.0 mm) | 2 sheets | 5–15 | 10–30 |
| | M3 screws + locating pins (interchangeable handle) | 2 sets | 2–5 | 4–10 |
| | Counterweight-rod material (brass rod Φ8 mm) | — | 5–10 | 5–10 |
| Auxiliary | PVA glue (250 ml) | 1 bottle | 15–25 | 15–25 |
| | Epoxy AB glue (50 g) | 1 set | 20–40 | 20–40 |
| | Polyurethane varnish | 1 small bottle | 15–30 | 15–30 |
| Tools | Electronic balance (0.01 g) | 1 | 40–80 | 40–80 |
| | Digital caliper (0.01 mm) | 1 | 30–60 | 30–60 |
| | G-clamps | 4 | 10–20 | 40–80 |
| | Sandpaper set (#80–#400) | 1 set | 15–30 | 15–30 |
| Rubbers | 729 FX SuperSoft 1.5 mm | 2 sheets | 35–45 | 70–90 |
| | LKT Pro XT 1.5 mm | 2 sheets (option) | 40–50 | 80–100 |

### 10.2 Budget by Scheme

| Scheme | Materials + fibre | Handle | Auxiliary + tools | Rubbers | **Total** |
| :--- | :-------: | :--: | :-------: | :--: | :------: |
| Scheme 1 (3-ply all-wood) | 50–80 | 10–25 | 120–255 | — | **180–360** |
| Scheme 2 (5-ply all-wood) | 70–100 | 10–25 | 120–255 | — | **200–380** |
| **Scheme 3 (5+2 ALC fibre)** | **110–250** | **20–70** | **140–275** | **80–120** | **250–715** |
| ~incl. rubbers (ultra-light)~ | — | — | — | 70–90 | ~320–805 |

> **Note**: the tools (balance, caliper, clamps, etc.) are a one-time investment and can be reused for subsequent schemes. If the tools are already available, subtract 100–175 CNY.

---

## 11 Recommended Execution Plan

### 11.1 Phased Execution Route

```
Phase 1: Prototype validation of Scheme 1 (3-ply all-wood)
├ Objective: validate the Limba + Balsa bonding process and make an initial assessment of feel
├ Budget: 60–105 CNY (materials only, reusing tools)
├ Duration: 1–2 days
└ Basis: Experiment 5 bonding strength ✅ / Experiment 7 process-parameter calibration ✅

Phase 2: Main fabrication of Scheme 3 (5+2 ALC fibre)
├ Objective: fabricate the blade of the final recommended scheme
├ Budget: 110–250 CNY (materials only)
├ Duration: 3–5 days (fibre-layer curing requires 24 h × 2)
└ Basis: Experiment 6 ALC-fibre performance verification ✅

Phase 3: Handle-module fabrication
├ Objective: fabricate the S/M/L interchangeable handles + counterweight rods
├ Budget: 20–70 CNY
├ Duration: 2–3 days
└ Basis: §6.2 advanced scheme design in the slim-handle report

Phase 4: Final assembly and testing
├ Objective: assemble the finished racket, measure weight/CG, and conduct trial hitting
├ Budget: 80–120 CNY (rubbers)
├ Duration: 1–2 days
└ Deliverable: the finished Octo table tennis racket
```

---

## 12 Material Procurement List

### 12.1 Priority Procurement (required for Scheme 3)

| # | Item | Specification | Quantity | Estimated price | Procurement channel |
| :-: | :--- | :--- | :-: | :------: | :------- |
| 1 | **Limba veneer** | 0.5–0.6 mm, ≥200×200 mm, knot-free | 3–5 sheets | 10–25 CNY/sheet | Taobao |
| 2 | **Kiri board** | 3–4 mm, density ~0.30 g/cm³ | 1–2 pieces | 20–50 CNY/piece | Taobao |
| 3 | **Balsa board** | Model-aircraft grade, density 0.15–0.20 g/cm³, 4–6 mm | 2–3 pieces | 15–40 CNY/piece | Taobao/model shop |
| 4 | **ALC fibre cloth** | Blue arylate-carbon blend, 200×200 mm | 1 sheet | 80–200 CNY/sheet | Taobao/table-tennis material shop |
| 5 | **Balsa strip** | 30×30×100 mm (handle body) | 2 strips | 5–10 CNY | Taobao/model shop |
| 6 | **Cork sheet** | 1.5–2.0 mm | 2 sheets | 5–15 CNY/sheet | Taobao |
| 7 | **PVA glue** | 250 ml | 1 bottle | 15–25 CNY | Offline/Taobao |
| 8 | **Epoxy AB glue** | ~50 g | 1 set | 20–40 CNY | Hardware store/Taobao |
| 9 | **M3 countersunk screws** | 12 mm long | 4 | 2 CNY | Hardware store |
| 10 | **Brass rod** | Φ8 × 50 mm (counterweight rod) | 1 length | 5–10 CNY | Hardware store |

### 12.2 Tools (one-time investment)

| # | Item | Quantity | Estimated price | Remarks |
| :-: | :--- | :-: | :------: | :--- |
| 11 | Electronic balance (0.01 g precision) | 1 | 40–80 CNY | Accurate weighing of each layer |
| 12 | Digital caliper (0.01 mm) | 1 | 30–60 CNY | Accurate thickness measurement |
| 13 | G-clamps / clamps | 4 | 10–20 CNY each | Pressurised fixing during bonding |
| 14 | Sandpaper (#80–#400 set) | 5 sheets each | 15–30 CNY | Sanding to shape |
| 15 | Drill press (optional) | 1 | 100–200 CNY | Drilling the counterweight chamber (a hand drill may be used instead) |
| 16 | Dust mask (N95) | 1 box | 20–40 CNY | Mandatory for safety |
| 17 | Nitrile gloves | 1 box | 20–40 CNY | For handling epoxy resin |

---

## 13 Final Benchmarking against Standard Rackets

| Parameter | Standard baseline | Octo final design | Change |
| :--- | :------: | :-----------: | :------: |
| **Total weight of finished racket** | 170–200 g | **124–137 g** | −30 % to −38 % ✅ |
| **Blade weight** | 82–95 g | **49–62 g** (adjustable with counterweights) | −25 % to −40 % ✅ |
| **Handle length** | 100 mm | **60–75 mm** (three interchangeable options) | −25 % to −40 % ✅ |
| **Handle circumference** | 85–95 mm | **65–80 mm** (three interchangeable options) | −15 % to −25 % ✅ |
| **CG position** | 46 %–50 % of total length | **48 %–58 % of total length** (adjustable with counterweights) | Marked rearward shift ✅ |
| **Blade thickness** | 5.5–7.0 mm | **5.68 mm** | Consistent with standard ✅ |
| **Structure type** | 5–7 plies | **7 plies (5+2 external ALC)** | Mainstream structure ✅ |
| **ITTF compliance** | ✅ | ✅ (wood >85 %, fibre layer <0.35 mm) | Compliant ✅ |

---

## 14 Summary

This design scheme integrates the research results of all three phases of the Octo project to form the final definitive scheme:

1. **Core scheme**: 5+2 external ALC fibre composite structure (Limba + ALC + Kiri + Balsa + Kiri + ALC + Limba), total thickness 5.68 mm, blade weight 49–62 g, finished-racket total weight 124–137 g, a 30 %–38 % weight reduction relative to standard rackets.

2. **Handle system**: a modular interchangeable-handle design (S/M/L three options, circumference 65–80 mm, length 60–75 mm) + a counterweight chamber at the handle end (W0–W3 counterweight rods selectable), enabling individualised fitting and CG adjustment (48 %–58 % of total length).

3. **Material selection**: all materials were selected on the basis of measured verification in the Phase-3 experiments—density (Experiment 1), hardness (Experiment 2), bending performance (Experiment 3), glue-uptake rate (Experiment 4), bonding strength (Experiment 5), fibre tension (Experiment 6), and process parameters (Experiment 7)—so the data are reliable.

4. **Process specification**: a complete nine-step manufacturing process flow and safety-protection requirements are provided, achievable under the conditions of a high-school student team.

5. **Controllable budget**: the material cost of the complete set including rubbers is approximately 320–805 CNY (including one-time tool investment), of which the core blade materials of Scheme 3 amount to approximately 110–250 CNY.

---

## References

[^1]: [Hand-Size and Grip-Strength Study of Dwarfism Patients](./%E9%98%B6%E6%AE%B51-%E5%89%8D%E7%BD%AE%E5%87%86%E5%A4%87/Research%20Report%20on%20Hand-Size%20and%20Grip-Strength%20of%20Dwarfism%20Patients.en.md)
[^2]: [Blade Base-Material Study](./%E9%98%B6%E6%AE%B51-%E5%89%8D%E7%BD%AE%E5%87%86%E5%A4%87/Research%20Report%20on%20Table%20Tennis%20Blade%20Materials.en.md)
[^3]: [Standard Racket Technical Baseline](./%E9%98%B6%E6%AE%B51-%E5%89%8D%E7%BD%AE%E5%87%86%E5%A4%87/Standard%20Table%20Tennis%20Racket%20Technical%20Parameter%20Baseline%20Report.en.md)
[^4]: [Lightweight Material Density and Price Survey](./%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Research%20Report%20on%20Density%20and%20Price%20of%20Lightweight%20Table%20Tennis%20Racket%20Materials.en.md)
[^5]: [Three Blade Design Schemes and Procurement List](./%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Three%20Blade%20Design%20Schemes%20and%20Procurement%20List.en.md)
[^6]: [Slim-Handle and Adjustable Handle Design Report](./%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Design%20Report%20on%20Slim-Handle%20and%20Adjustable%20Counterweight%20and%20Length%20Handles.en.md)
[^7]: [Wood and Fiber Material Performance Test Report](./%E9%98%B6%E6%AE%B53-%E5%AE%9E%E9%AA%8C%E4%B8%8E%E6%B5%8B%E8%AF%95/Phase-3%20Experiment%20Report%20on%20Performance%20Testing%20of%20Wood%20and%20Fibre%20Materials.en.md)
[^8]: [Experimental Safety Instructions](./Experimental%20Safety%20Instructions.en.md)
[^9]: International Table Tennis Federation. (2025). *Table Tennis Rules* (Chapter 2). ITTF.







