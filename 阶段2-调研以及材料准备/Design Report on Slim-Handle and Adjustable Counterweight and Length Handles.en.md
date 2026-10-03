# Design Report on a Slim-Handle Racket and an Adjustable Counterweight/Length Handle

## 1 Introduction

In the design objectives of the Octo table tennis racket, **handle optimisation** is as important as **racket lightweighting**. According to the data of [Hand-Size and Grip-Strength Study of Dwarfism Patients](../%E9%98%B6%E6%AE%B51-%E5%89%8D%E7%BD%AE%E5%87%86%E5%A4%87/Research%20Report%20on%20Hand-Size%20and%20Grip-Strength%20of%20Dwarfism%20Patients.en.md), the target users' palm width is only **6.0–8.0 cm** (markedly below the 5th percentile of the normal population), whereas the handle circumference of a standard shakehand racket is **85–95 mm** and its length **100 mm**, far exceeding the target users' gripping capacity.

On the basis of the material selection in [Lightweight Material Density and Price Survey](./Research%20Report%20on%20Density%20and%20Price%20of%20Lightweight%20Table%20Tennis%20Racket%20Materials.en.md), this report proposes systematic design schemes for slim handles and for adjustable counterweight/length handles. The report covers the following content:

- **Ergonomics-driven factors**: derivation of the handle geometric parameters based on hand-size characteristics
- **Fixed slim-handle design schemes**: dimensions, materials, and structure of ultra-short, ultra-slim handles
- **Adjustable-length handle schemes**: modular designs that adapt to different palm widths and grip preferences
- **Adjustable counterweight system schemes**: counterweight mechanisms that achieve a rearward CG shift and individualised adjustment
- **Structural strength and manufacturability**: evaluation of the fabrication process and feasibility of each scheme
- **Benchmarking of the design schemes**: quantitative comparison with the Phase-1 baseline data

---

## 2 Ergonomic Analysis and Derivation of Handle Parameters

### 2.1 Review of Target-User Hand Size

According to [Hand-Size and Grip-Strength Study of Dwarfism Patients](../%E9%98%B6%E6%AE%B51-%E5%89%8D%E7%BD%AE%E5%87%86%E5%A4%87/Research%20Report%20on%20Hand-Size%20and%20Grip-Strength%20of%20Dwarfism%20Patients.en.md), the key design input parameters are as follows:

| Parameter | Adult male | Adult female | Reference for the normal population (male P50) | Design basis |
| :--- | :------: | :------: | :---------------------: | :------- |
| Palm width (cm) | 6.5–8.0 | 6.0–7.5 | 8.2 | Determines the upper limit of handle circumference |
| Palm length (cm) | 7–9 | 6–8 | about 10 | Determines the upper limit of handle length |
| Middle-finger length (cm) | 5–6.5 | 4.5–5.5 | about 8 | Affects the handle cross-sectional shape |
| Maximum grip duration | — | — | — | Affects the choice of material (friction, sweat absorption) |

### 2.2 Derivation of Handle Geometric Parameters

The handle design parameters and the hand dimensions follow the constraint relationships below:

**Upper limit of handle circumference**: for a "forehand-oriented" grip, when the palm wraps around the handle the distance between the thumb and the middle finger must be able to enclose it naturally. The empirical relationship between the handle circumference $C$ and the palm width $W$ is:

$$C_{\text{max}} \approx 0.85 \times W \times \pi$$

When the palm width $W = 65\text{–}80\ \text{mm}$, the calculation gives $C_{\text{max}} = 65\text{–}80\ \text{mm}$.

**Upper limit of handle length**: the handle should be shorter than the palm length, to avoid extending too far beyond the web between the thumb and the index finger. Recommended:

$$L_{\text{handle}} \leq 0.85 \times L_{\text{palm}}$$

When the palm length $L_{\text{palm}} = 70\text{–}90\ \text{mm}$, $L_{\text{handle}} = 60\text{–}75\ \text{mm}$.

**Cross-section design constraint**: the cross-sectional height (in the thickness direction) of the handle should not exceed 60 % of the middle-finger length, to prevent the fingers being unable to wrap around the handle:

$$H_{\text{section}} \leq 0.60 \times L_{\text{middle finger}}$$

When the middle-finger length $L_{\text{middle}} = 45\text{–}65\ \text{mm}$, $H_{\text{section}} \leq 27\text{–}39\ \text{mm}$.

### 2.3 Recommended Design Parameters

Based on the above derivation, the following handle geometric-parameter ranges are proposed:

| Design parameter | Octo recommended value | Reference value for a standard shakehand racket | Change |
| :------- | :---------: | :------------: | :------: |
| Handle circumference | 65–80 mm | 85–95 mm | **15 %–25 % reduction** |
| Handle length | 60–75 mm | 100 mm | **25 %–40 % shortening** |
| Handle width (left–right direction) | 22–26 mm | 28–34 mm | 18 %–25 % reduction |
| Handle thickness (front–back direction) | 18–22 mm | 23–26 mm | 10 %–18 % reduction |
| Cross-sectional shape | Elliptical / octagonal | FL / ST / AN | — |
| Surface friction coefficient | ≥ 0.4 (sweat band/cork) | 0.2–0.3 (smooth varnish) | — |

> **Table 1: Comparison of the Octo handle design parameters with the standard baseline**

---

## 3 Fixed Slim-Handle Design Schemes

### 3.1 Scheme A: One-Piece Short Handle (Reduced-Size FL)

#### 3.1.1 Structural Description

The standard FL (waisted) handle is directly scaled down proportionally, retaining the contour characteristics of an FL handle (a narrowed middle for easy forehand/backhand switching) but reducing the overall dimensions by about 25 %–30 %.

#### 3.1.2 Dimensional Parameters

| Parameter | Reduced-size FL | Standard FL reference |
| :--- | :--------: | :----------: |
| Total length | 70 mm | 100 mm |
| Front-end width | 24 mm | 30 mm |
| Minimum width at the waist | 18 mm | 24 mm |
| Rear-end width | 26 mm | 34 mm |
| Thickness (front end) | 18 mm | 23 mm |
| Thickness (rear end) | 20 mm | 25 mm |
| Weight | 12–15 g | 18–22 g |

> **Table 2: Comparison of the reduced-size FL handle with the standard FL handle**

#### 3.1.3 Material Selection

| Component | Material | Density (g/cm³) | Remarks |
| :--- | :--- | :----------: | :--- |
| Handle body | Balsa / Ayous | 0.15–0.35 | Lightweight; Balsa can reduce weight further but requires hardwood edge banding |
| Surface covering | Cork sheet | 0.15–0.25 | Anti-slip, sweat-absorbing; a thickness of 1.5–2.0 mm is recommended |
| Handle-end decoration | Ebony/rosewood veneer | 0.90–1.10 | Optional; used to close off the end of the handle |

> **Table 3: Recommended material combination for the one-piece short handle**

#### 3.1.4 Applicability and Limitations

- **Advantages**: the simplest structure, the easiest to fabricate (CNC or hand sanding), and the lowest cost.
- **Disadvantages**: fixed dimensions, unable to accommodate a user group with large individual variation; cannot be replaced once bonded.

---

### 3.2 Scheme B: Two-Piece Interchangeable Handle (Modular Interface)

#### 3.2.1 Structural Description

The handle is designed as an independent module that is separable from the blade and connected to the racket face through a mechanical interface (screws + locating pins). Users can freely swap between several handle modules of different sizes.

#### 3.2.2 Interface Design

A connection scheme of **M3 × 12 mm countersunk machine screws × 2 + locating pins × 2** is used:

```
Blade handle extension (tang)
┌──────────────────────────────────────┐
│  ● ← M3 screw holes × 2 (countersunk)│
│  ┊ ← Locating-pin holes × 2          │
└──────────────────────────────────────┘
           ↓ Butt-join and insert
┌──────────────────────────────────────┐
│  ● ← M3 studs × 2                    │
│  ┊ ← Locating pins × 2               │
│  [Handle-module body]                 │
└──────────────────────────────────────┘
```

**Design points**:

- The tang is 30–35 mm long and is embedded inside the handle body.
- The screw holes are 10 mm and 30 mm from the end of the handle, ensuring connection rigidity.
- The locating pins are 2 mm in diameter and 5 mm deep, preventing the handle from rotating or shifting.
- The screws are stainless steel, with a total weight of about 1.5 g.

#### 3.2.3 Handle-Module Series

| Model | Length (mm) | Circumference (mm) | Cross-sectional shape | Applicable palm width (cm) | Weight (g) |
| :--- | :-------: | :-------: | :------: | :-----------: | :------: |
| S | 60 | 65 | Elliptical | 6.0–6.5 | 10–12 |
| M | 68 | 72 | Elliptical | 6.5–7.0 | 12–14 |
| L | 75 | 80 | Elliptical/octagonal | 7.0–8.0 | 14–17 |

> **Table 4: Parameters of the interchangeable handle-module series**

#### 3.2.4 Applicability and Limitations

- **Advantages**: highly customisable; one blade fits different users; the handle can be replaced separately once worn.
- **Disadvantages**: the interface adds structural complexity and weight (about 1.5 g); the screws may loosen during long-term use and require periodic tightening; higher fabrication precision is required.

---

### 3.3 Scheme C: Extended One-Piece Handle (No Conventional Handle)

#### 3.3.1 Structural Description

The concept of a conventional separate handle is completely abandoned, and the handle portion of the racket face is extended directly as the gripping area, with the racket-face wood and the handle being the same piece of timber and the surface then being wrapped with cork or a sweat band.

#### 3.3.2 Dimensional Parameters

```
┌──────────────────────────────────┐
│      Racket face (~157 × 150 mm)  │
│                                   │
│     ┌─────────────────────┐       │
│     │ Integrated extended  │       │
│     │ grip area            │       │
│     │ length 60–70 mm      │       │
│     │ width 22–26 mm       │       │
│     └─────────────────────┘       │
└──────────────────────────────────┘
```

- Extension length: 60–70 mm
- Extension width: 22–26 mm
- Extension thickness: 15–18 mm (multiple wood layers stacked to the required thickness)
- Total weight (extension + covering layer): 8–12 g

#### 3.3.3 Applicability and Limitations

- **Advantages**: minimalist structure, no interface, lightest weight (6–10 g lighter than a conventional handle); no risk of loosening.
- **Disadvantages**: cannot be replaced or adjusted; the appearance differs greatly from a conventional racket, which may affect psychological acceptance; users must adapt to the gripping method.

---

## 4 Adjustable-Length Handle Design Schemes

### 4.1 Telescopic Handle (Scheme D)

#### 4.1.1 Structural Description

The handle is divided into two parts, an **inner core** and an **outer sleeve**: the inner core is fixed to the blade tang, and the outer sleeve can slide axially along the inner core and be fixed at different positions by a locking mechanism, thereby adjusting the length.

```
┌─────────────────────────────────────┐
│  Blade tang (fixed part)             │
│  ┌───────────────────────┐           │
│  │ Inner core (fixed)     │           │
│  └───────────────────────┘           │
│  ┌───────────────────────┐           │
│  │ Outer sleeve (slidable)│  ← adjustment range
│  └───────────────────────┘           │
│       ▲                              │
│       └── Locking screw/clip          │
└─────────────────────────────────────┘
```

#### 4.1.2 Design Scheme

| Component | Material | Function |
| :--- | :--- | :--- |
| Inner core (fixed) | Hardwood (ebony/beech) | Integrated with the blade tang, providing guidance and structural strength |
| Outer sleeve (slidable) | ABS engineering plastic / lightweight wood + carbon-fibre skin | The external gripping part, sliding along the inner core |
| Locking mechanism | M4 stainless-steel thumbscrew + nylon insert | Compresses the inner core when tightened, preventing sliding |
| Limit end cap | ABS plastic | Fixed to the end of the inner core, preventing the outer sleeve from coming off |

#### 4.1.3 Adjustment Performance

| Parameter | Minimum value | Maximum value | Adjustment travel |
| :--- | :----: | :----: | :------: |
| Handle length | 55 mm | 75 mm | 20 mm |
| Handle circumference | 70 mm | 72 mm | Constant (the sleeve cross-section does not change) |
| Handle weight | 14 g | 16 g | Essentially constant |

#### 4.1.4 Structural-Strength Requirements

- Locking force: the outer sleeve must not slide axially under a torque load of 30 N·m (corresponding to a safety margin for a swing centrifugal acceleration of ~10 g).
- Fatigue life: the adjustment mechanism can still lock after ≥500 cycles.
- Lateral stiffness: deflection ≤1.5 mm when the handle is subjected to a lateral force of 50 N.

#### 4.1.5 Applicability and Limitations

- **Advantages**: one handle fits many hand lengths; stepless adjustment for precise fitting; compact structure.
- **Disadvantages**: complex structure and relatively high fabrication difficulty; the locking mechanism may loosen during use; the highest cost (estimated 30–60 CNY/set); the feel may be inconsistent at the extreme adjustment positions.

---

### 4.2 Replaceable Length Modules (Scheme E)

#### 4.2.1 Structural Description

Based on the modular interface of Scheme B (two-piece interchangeable handle), handle modules of different lengths are provided (the S/M/L length differences in Scheme B already realise a length-adjustment function); users change the handle length by swapping modules.

The difference from Scheme D is:

- **Scheme D (telescopic)**: continuous stepless adjustment, no spare parts required.
- **Scheme E (replaceable)**: discrete-step adjustment, requiring multiple modules.

#### 4.2.2 Performance Comparison

| Comparison item | Scheme D (telescopic) | Scheme E (replaceable) |
| :----- | :-------------: | :-------------: |
| Adjustment method | Stepless telescoping | Module replacement |
| Adjustment range | 55–75 mm | 60/68/75 mm (three steps) |
| Handle feel | The sleeve is thicker, feel on the hard side | Genuine wood texture, natural feel |
| Structural complexity | ★★★★★ (high) | ★★★☆☆ (medium) |
| Manufacturing cost | 30–60 CNY/set | 10–15 CNY/module + interface |
| Reliability | ★★★ | ★★★★★ |
| Extra weight | +3–5 g (locking mechanism) | +1.5 g (screw interface) |

> **Table 5: Telescopic vs. replaceable length-adjustment schemes**

---

## 5 Adjustable Counterweight System Design

### 5.1 Counterweight Design Objectives

According to [Standard Racket Technical Baseline](../%E9%98%B6%E6%AE%B51-%E5%89%8D%E7%BD%AE%E5%87%86%E5%A4%87/Standard%20Table%20Tennis%20Racket%20Technical%20Parameter%20Baseline%20Report.en.md), the CG of a standard shakehand racket lies at 46 %–50 % of the total length from the racket-head top, whereas Octo needs to shift the CG **markedly towards the handle**, to reduce the moment of inertia and improve control sensitivity.

The counterweight system must meet the following objectives:

| Objective | Quantitative indicator | Significance |
| :----- | :---------------------: | :------- |
| CG position | **>52 %** of total length from the racket-head top, or biased towards the handle | Reduce the swing moment of inertia |
| Adjustable total weight | Blade 55–70 g, full racket 110–130 g | Adapt to different strength levels |
| Counterweight adjustment range | At least ±3 g effective counterweight change | Enable fine CG adjustment |
| Ease of operation | Adjustable without tools | Improve usability |

### 5.2 Counterweight-Position Analysis

Three main positions on the racket where a counterweight can be placed, and their effects:

| Position | Distance from the CG reference point | Effect on the CG | Effect on the moment of inertia |
| :--- | :--------------: | :------------: | :------------: |
| **Handle end** (position ①) | ~90 mm (far from the CG) | **★★★★★** | Markedly reduces racket-head inertia |
| **Middle of the handle** (position ②) | ~50 mm | **★★★** | Moderate |
| **Bottom of the racket face** (position ③) | Close to the CG | **★** | Very small |

**Strategy**: place the counterweight at the handle end (position ①), to achieve the greatest rearward CG shift with the least weight.

### 5.3 Scheme F: Built-in Adjustable Counterweight Chamber in the Handle

#### 5.3.1 Structural Description

A cylindrical counterweight chamber (diameter 8–10 mm, depth 20–30 mm) is opened at the handle end, holding counterweight rods of different weights; users can unscrew the end cap to change the counterweight.

```
Handle end
┌───────────────────────────────┐
│  ┌─────────────────────┐      │
│  │ CW chamber (Φ8 × 25 mm)│    │
│  │ ┌─┐ ┌─┐ ┌─┐         │      │
│  │ │ │ │ │ │ │ ← CW rods │      │
│  │ └─┘ └─┘ └─┘         │      │
│  └─────────────────────┘      │
│   ○ ← Screw cap (with O-ring) │
└───────────────────────────────┘
```

#### 5.3.2 Counterweight-Rod Specifications

| Model | Material | Diameter × length | Weight | Relative effect |
| :--- | :--- | :---------: | :--: | :------: |
| W0 | Cork/plastic (empty) | Φ8 × 25 mm | ~1 g | No counterweight (baseline) |
| W1 | Brass | Φ8 × 25 mm | ~9 g | CG shifts rearward by about 4 mm |
| W2 | Stainless steel | Φ8 × 25 mm | ~8 g | CG shifts rearward by about 3.5 mm |
| W3 | Lead (must be encapsulated) | Φ8 × 25 mm | ~12 g | CG shifts rearward by about 5 mm |

> **Table 6: Counterweight-rod specification table**
>
> Note: the effect on the rearward CG shift is estimated on the basis of a total racket length of 220–240 mm (racket face 155 mm + handle 65–85 mm). The actual effect varies with the specific racket dimensions and the original weight distribution.

#### 5.3.3 Estimation of the Counterweight Effect

Calculated for a typical configuration with a blade total weight of 60 g and a total racket length of 230 mm:

| Counterweight configuration | Counterweight weight | CG position (from the racket-head top) | Change in moment of inertia |
| :------- | :------: | :------------------: | :----------: |
| No counterweight (W0) | ~1 g | ~100 mm (43.5 %) | Baseline |
| W1 (brass) | ~9 g | ~108 mm (47.0 %) | −8 % |
| W2 (stainless steel) | ~8 g | ~107 mm (46.5 %) | −7 % |
| W3 (lead) | ~12 g | ~112 mm (48.7 %) | −12 % |

> **Table 7: Estimated influence of different counterweights on the CG position and the moment of inertia**
>
> Note: even with the heaviest counterweight (W3, 12 g), together with the handle's own 12–15 g, the total handle weight remains within an acceptable range.

### 5.4 Scheme G: Counterweight Slot at the Bottom of the Racket Face

#### 5.4.1 Structural Description

Replaceable metal counterweight plates are embedded at the bottom of the racket face (near the tang region), at the junction between the racket face and the handle. This region is close to the swing rotation axis, so its influence on the moment of inertia is small, but it can finely adjust the total weight and the feel.

#### 5.4.2 Counterweight-Plate Design

```
Bottom of the racket face (front end of the handle)
┌──────────────────────────────┐
│  ┌──────────────────┐        │
│  │ CW slot (20×10×3 mm)│     │
│  │ [counterweight plate]│    │
│  └──────────────────┘        │
└──────────────────────────────┘
```

| Counterweight plate | Material | Weight | Effect |
| :----- | :--- | :--: | :--- |
| G0 | None (empty slot) | 0 g | Lightest configuration |
| G1 | Copper plate | ~5.4 g | Increase in total weight, slight CG shift |
| G2 | Steel plate | ~4.7 g | Increase in total weight, slight CG shift |

### 5.5 Comparison of Counterweight Schemes

| Comparison item | Scheme F (built-in counterweight chamber in the handle) | Scheme G (counterweight slot in the racket face) |
| :----- | :------------------: | :----------------: |
| CG influence | ★★★★★ (marked rearward shift) | ★★ (slight shift) |
| Total-weight adjustment | ★★★★ (±10 g range) | ★★★ (±5 g range) |
| Structural complexity | ★★★ (requires a blind hole and a threaded cap) | ★ (only requires milling a slot) |
| Manufacturing cost | +5–10 CNY | +2–5 CNY |
| Operability | Unscrew the cap to change, convenient | Requires opening the rubber covering, inconvenient |
| Recommended use | **Main counterweight method** | Auxiliary fine adjustment of total weight |

> **Table 8: Comparison of the counterweight schemes**

---

## 6 Comprehensive Design-Scheme Recommendations

Taking into account the advantages and limitations of the above schemes, the following **tiered configuration schemes** are recommended:

### 6.1 Basic Scheme (Entry Level — Fixed Slim Handle)

| Component | Choice | Design basis |
| :--- | :--- | :------- |
| Handle type | Scheme A: one-piece short FL | Simplest structure, easiest to fabricate |
| Handle size | Total length 70 mm, circumference 72 mm | Fits the median user with a palm width of 6.5–7.5 cm |
| Handle material | Ayous body + cork sheet | Lightweight and anti-slip, low cost |
| Counterweight method | None (the CG is ensured by the material gradient) | Simplifies the design, reduces cost |
| Estimated handle weight | 13–15 g | — |
| Estimated material cost | 5–10 CNY (handle part) | — |

**Applicable scenarios**: initial prototyping, cost-sensitive, single fixed user.

### 6.2 Advanced Scheme (Intermediate — Interchangeable Handle + Counterweight)

| Component | Choice | Design basis |
| :--- | :--- | :------- |
| Handle type | Scheme B: two-piece interchangeable handle | Modular, suitable for multiple users |
| Handle size | S / M / L three steps | Covers palm widths 6.0–8.0 cm |
| Handle material | Balsa (light) + hardwood interface end | The interface end must be wear-resistant; the grip area must be light |
| Counterweight method | Scheme F: built-in counterweight chamber in the handle | Counterweight rods × 3–4 types selectable |
| Counterweight material | Brass/stainless steel (encapsulated against oxidation) | Safe, durable |
| Estimated handle weight | 12–18 g (incl. counterweight chamber) | Excluding counterweight rods |
| Estimated material cost | 30–50 CNY (incl. the complete handle-module set) | — |

**Applicable scenarios**: shared by multiple users, individualised fitting required, pursuit of optimal CG control.

### 6.3 Flagship Scheme (Advanced — Telescopic + Counterweight)

| Component | Choice | Design basis |
| :--- | :--- | :------- |
| Handle type | Scheme D: telescopic + Scheme F: counterweight chamber | Stepless adjustment + CG control |
| Handle size | Continuous adjustment 55–75 mm | The widest fitting range |
| Handle material | Hardwood inner core + carbon-fibre-reinforced plastic sleeve | Balances strength and lightweighting |
| Counterweight method | Scheme F (counterweight chamber) + Scheme G (counterweight slot in the racket face) | Dual-counterweight system |
| Counterweight range | ±12 g (handle counterweight + racket-face counterweight) | Flexible adjustment |
| Estimated handle weight | 16–22 g (incl. the adjustment mechanism) | Slightly heavier but feature-rich |
| Estimated material cost | 60–100 CNY (incl. the complete mechanism) | — |

**Applicable scenarios**: pursuit of the ultimate fit, research validation, high-end customisation.

---

## 7 Verification of Centre-of-Gravity Positioning and Counterweight Calculation

### 7.1 Calculation Model

Simplified blade model: the racket is treated as a combination of the racket face (outer ply + medial ply + core + fibre) and the handle, with the CG of each part located at its own geometric centre.

- Racket-face mass $m_{\text{blade}}$ = 35–45 g (excluding the handle)
- Handle mass $m_{\text{handle}}$ = 10–18 g
- Counterweight mass $m_{\text{cw}}$ = 0–12 g
- Racket-face total length $L_{\text{blade}}$ = 157 mm (in the height direction)
- Handle total length $L_{\text{handle}}$ = 60–75 mm
- Racket-face CG from the racket-head top ≈ $L_{\text{blade}} / 2 = 78.5\ \text{mm}$
- Handle CG from the racket-head top ≈ $L_{\text{blade}} + L_{\text{handle}} / 2$
- The counterweight is regarded as being at the handle end

### 7.2 Calculation for a Typical Configuration

Taking the **advanced scheme** as an example, using the median parameters:

| Component | Mass (g) | CG distance from racket-head top (mm) | Moment (g·mm) |
| :--- | :------: | :-----------------: | :---------: |
| Racket face (bare blade) | 38.0 | 78.5 | 2,983 |
| Handle (basic) | 14.0 | 193.0 | 2,702 |
| Counterweight W1 (brass) | 9.0 | 222.5 | 2,003 |
| **Total** | **61.0** | — | **7,688** |

Overall CG position:

$$x_{\text{CG}} = \frac{7,688\ \text{g·mm}}{61.0\ \text{g}} = 126.0\ \text{mm}$$

Total racket length $L_{\text{total}} = 157 + 70 = 227\ \text{mm}$; the CG as a percentage of the total length:

$$\frac{126.0}{227} = 55.5\%$$

**Conclusion**: after counterweighting, the CG lies at **55.5 % of the total length**, markedly biased towards the handle (versus 46 %–50 % for a standard shakehand racket), effectively reducing the moment of inertia.

### 7.3 CG Position for Different Counterweight Configurations

| Counterweight configuration | Total weight (g) | CG from racket top (mm) | CG percentage | Rearward shift vs. standard |
| :------- | :------: | :-------------: | :--------: | :-------------: |
| No counterweight (W0) | 52.0 | 109.4 | 48.2 % | Close to the standard handle-biased value |
| W1 (brass, 9 g) | 61.0 | 126.0 | 55.5 % | Marked rearward shift |
| W2 (stainless steel, 8 g) | 60.0 | 124.3 | 54.8 % | Marked rearward shift |
| W3 (lead, 12 g) | 64.0 | 130.6 | 57.5 % | Extreme rearward shift |

> **Table 9: Influence of different counterweights on the CG position**
>
> Note: the CG percentage of a standard shakehand racket is 46 %–50 % (from the racket-head top). The Octo target is >52 %.

### 7.4 Total-Weight Reconciliation of Blade + Handle + Counterweight

| Source | Item | Weight (g) |
| :--- | :--- | :------: |
| [Lightweight Material Density and Price Survey](./Research%20Report%20on%20Density%20and%20Price%20of%20Lightweight%20Table%20Tennis%20Racket%20Materials.en.md) Scheme A' (5+2 fibre, ZLF) | Bare racket face (incl. glue) | 38 |
| — | Surface coating | 2–3 |
| — | Handle (basic 14 g + counterweight chamber +2 g) | 16 |
| — | Counterweight rod (W0/W1/W2/W3) | 1/9/8/12 |
| — | Screw interface (interchangeable-handle schemes only) | 1.5 |
| **Blade total weight (no counterweight)** | | **~57.5 g** |
| **Blade total weight (incl. W1 counterweight)** | | **~66.5 g** |
| Rubbers ([Lightweight Material Density and Price Survey](./Research%20Report%20on%20Density%20and%20Price%20of%20Lightweight%20Table%20Tennis%20Racket%20Materials.en.md) ultra-light scheme) | Forehand 36 + backhand 36 + glue 3 | 75 |
| **Finished total weight (no counterweight)** | | **~132.5 g** |
| **Finished total weight (incl. W1 counterweight)** | | **~141.5 g** |
| **Octo target total weight** | | **110–130 g** |

> **Table 10: Total-weight reconciliation**

**Analysis**: when the ZLF fibre scheme + ultra-light rubbers (75 g) are used, the finished total weight is about 132.5 g (no counterweight) to 141.5 g (with counterweight), slightly above the 130 g upper target limit. Solutions:

1. Use the ultra-light Scheme C in [Lightweight Material Density and Price Survey](./Research%20Report%20on%20Density%20and%20Price%20of%20Lightweight%20Table%20Tennis%20Racket%20Materials.en.md) (Balsa core, blade ~48 g); the total weight can then drop to 48 + 16 + 75 = **139 g** (with counterweight) and 129 g (without counterweight).
2. Further thin the medial ply/outer ply by 0.1 mm, saving another 1–2 g.
3. Treat the counterweight as an optional accessory; it may be left off for daily use and installed only when needed.

---

## 8 Handle Material Selection and Surface Treatment

### 8.1 Base-Material Selection

| Material | Density (g/cm³) | Applicable scheme | Advantages | Disadvantages |
| :--- | :----------: | :------: | :--- | :--- |
| Ayous | 0.29–0.45 | A, B | Light and tough, low price | Relatively soft surface, requires coating protection |
| Balsa | 0.10–0.20 | A, B | Extremely light, good vibration damping | Too soft, requires a hardwood-reinforced interface |
| Hinoki | 0.35–0.50 | A | Soft feel, attractive grain | Relatively expensive |
| Kiri | 0.23–0.40 | A | Lightweight, good stability | Too soft |
| Ebony/beech | 0.90–1.10 | D (inner core) | High strength, wear-resistant | Heavy; limited to interface/inner-core use |

### 8.2 Surface Covering and Anti-Slip Treatment

| Scheme | Material | Thickness | Friction coefficient | Vibration-damping effect | Cost |
| :--- | :--- | :--: | :------: | :------: | :--: |
| **Cork sheet** | Natural cork | 1.5 mm | 0.40–0.55 | ★★★★ | Low |
| **Sweat-band wrapping** | PU sweat band | 0.5–0.8 mm | 0.35–0.50 | ★★★ | Very low |
| **Heat-shrink grip sleeve** | Rubber/silicone | 1.0 mm | 0.45–0.60 | ★★★ | Low |
| **Wood wax oil coating** | Natural wood wax oil | — | 0.20–0.30 | ★ | Very low |
| **Polyurethane varnish** | PU varnish | 0.1–0.2 mm | 0.15–0.25 | ★ | Very low |

> **Table 11: Comparison of handle surface-treatment schemes**
>
> **Recommendation**: cork sheet (preferred) or sweat-band wrapping (alternative), balancing anti-slip, sweat absorption, vibration damping, and cost.

---

## 9 Fabrication Process and Implementation Scheme

### 9.1 Assessment of Fabrication Difficulty of the Different Schemes

| Scheme | Fabrication method | Required equipment | Skill requirement | Fabrication time | Applicable stage |
| :--- | :------- | :------- | :------: | :------: | :------- |
| A One-piece short handle | Hand sanding / CNC carving | Sandpaper, files / CNC | Medium / low | 1–3 h | **Prototyping/mass production** |
| B Two-piece interchangeable handle | CNC + hand drill + tap | CNC, drill press, M3 tap | High | 3–5 h | Prototype validation |
| C Extended one-piece | Hand sanding | Sandpaper, files | Medium | 1–2 h | **Prototyping/mass production** |
| D Telescopic | 3D-printed sleeve + CNC inner core | 3D printer, CNC | High | 5–10 h | Prototype validation |
| E Replaceable modules | CNC + hand drill | CNC, drill press | Medium-high | 3–5 h | Prototype validation |
| F Counterweight chamber | Drill-press drilling + tap | Drill press, M10×1 tap | Medium | 0.5–1 h | Prototyping/mass production |
| G Counterweight slot | CNC slot milling | CNC | Medium | 0.5–1 h | Prototyping/mass production |

### 9.2 Recommended Process Route for the Prototyping Stage

For a high-school student project team, a hybrid route based mainly on **manual machining** with **3D printing/CNC** as a supplement is recommended:

```
Step 1: Cut the handle blank (coping saw or band saw)
    ↓
Step 2: Coarse-sand to the target dimensions (file + sandpaper #80–#120)
    ↓
Step 3: Open the counterweight chamber (hand drill Φ8 mm + M10×1 tap)
    ↓
Step 4: Fine-sand to final shape (sandpaper #240–#400)
    ↓
Step 5: Attach cork or wrap a sweat band on the surface
    ↓
Step 6: Install the counterweight (screw in the counterweight rod + cap)
    ↓
Step 7: Assemble to the blade (gluing or screw fixing)
```

### 9.3 Safety Notes

- Wear a **dust mask** when machining wood (wood dust can cause allergies).
- Fix the workpiece and wear safety goggles when using a hand drill/drill press.
- Use epoxy resin/glue in a ventilated place.
- Avoid using **pure lead** in the counterweight material (toxic). If a high-density counterweight is required, use an encapsulated lead rod or substitute with tungsten alloy/brass.

---

## 10 Quantitative Benchmarking of the Design Scheme

### 10.1 Comprehensive Comparison with the Standard Baseline

| Parameter | Standard baseline | Octo recommended scheme | Change |
| :--- | :------: | :-----------: | :------: |
| **Handle length** | 100 mm | 60–75 mm (adjustable) | **−25 % to −40 %** |
| **Handle circumference** | 85–95 mm | 65–80 mm | **−15 % to −25 %** |
| **Handle cross-section** | FL/ST/AN standard shapes | Reduced-size elliptical/octagonal | More ergonomic grip |
| **Handle weight** | 18–22 g | 10–18 g (adjustable) | **−18 % to −45 %** |
| **Handle material** | A single hardwood | Light wood + cork, two materials | Weight reduction + anti-slip |
| **Counterweight range** | None (fixed) | ±12 g (optional) | **New function** |
| **CG position** | 46 %–50 % (racket head relatively heavy) | 48 %–58 % (adjustable to handle-biased) | **Rearward CG shift** |
| **Finished total weight** | 170–200 g | 110–130 g | **−30 % to −40 %** |

> **Table 12: Comprehensive comparison of the Octo handle design with the standard baseline**

### 10.2 Benchmarking against the Design Recommendations in [Hand-Size and Grip-Strength Study of Dwarfism Patients](../%E9%98%B6%E6%AE%B51-%E5%89%8D%E7%BD%AE%E5%87%86%E5%A4%87/Research%20Report%20on%20Hand-Size%20and%20Grip-Strength%20of%20Dwarfism%20Patients.en.md)

| Report recommendation | Realisation in this design | Degree of satisfaction |
| :------- | :--------- | :------: |
| Handle circumference 65–80 mm | 65–80 mm (three interchangeable or adjustable options) | ✅ Fully satisfied |
| Handle length 60–75 mm | 55–75 mm (slightly larger adjustment range) | ✅ Fully satisfied |
| Elliptical/octagonal cross-section | Elliptical (interchangeable handle) + octagonal (optional feel) | ✅ Fully satisfied |
| Cork/sweat band | Cork sheet / PU sweat band | ✅ Fully satisfied |
| Adjustable handle | Interchangeable handle modules / telescopic | ✅ Fully satisfied |
| Adjustable counterweight | Counterweight chamber + counterweight slot, dual system | ✅ Fully satisfied |
| Total weight 110–130 g | 129–142 g (racket-face/rubber combination needs optimisation) | ⚠️ Partially satisfied (see Section 7.4) |

> **Table 13: Benchmarking against the design recommendations**

---

## 11 Conclusions and Recommendations

### 11.1 Core Conclusions

1. **The slim-handle design theory is mature**: according to the ergonomic derivation, the Octo handle circumference must be reduced to 65–80 mm (standard 85–95 mm) and the length shortened to 60–75 mm (standard 100 mm), a reduction of 15 %–40 %, consistent with the research data in [Hand-Size and Grip-Strength Study of Dwarfism Patients](../%E9%98%B6%E6%AE%B51-%E5%89%8D%E7%BD%AE%E5%87%86%E5%A4%87/Research%20Report%20on%20Hand-Size%20and%20Grip-Strength%20of%20Dwarfism%20Patients.en.md).
2. **All three fixed slim-handle schemes are feasible**:
   - **Scheme A (one-piece short handle)**: the simplest scheme, easy to fabricate; recommended for priority use at the prototyping stage.
   - **Scheme B (two-piece interchangeable handle)**: modular design, suitable for multiple users; recommended for advanced use.
   - **Scheme C (extended one-piece)**: the lightest scheme, but requires user adaptation; suitable for extreme lightweighting.
3. **The comparison of length-adjustment schemes is clear**: the telescopic type (Scheme D) provides the best fit but has a complex structure, while the replaceable type (Scheme E) has high reliability but demands more initiative from users. **Priority use of Scheme E (replaceable modules) is recommended.**
4. **The counterweight system effectively achieves a rearward CG shift**: the built-in counterweight chamber in the handle (Scheme F) can provide a counterweight range of ±12 g, moving the CG from 48 % to 58 % of the total length and markedly reducing the moment of inertia.
5. **There is still room for weight optimisation**: combining the lightest configuration (Balsa core + ZLF fibre + ultra-light rubbers + basic handle), the finished total weight is about 129 g, essentially entering the 110–130 g target range.

### 11.2 Recommended Implementation Route

Given the high-school student team background of the project, the following phased implementation route is recommended:

| Phase | Content | Estimated time | Budget |
| :--- | :--- | :------: | :--: |
| Phase 1 | Make 2–3 samples of the Scheme A one-piece short handle | 1–2 days | 20–30 CNY |
| Phase 2 | After verifying ergonomic comfort, make one each of the Scheme B interchangeable-handle modules S/M/L + a counterweight chamber | 3–5 days | 50–80 CNY |
| Phase 3 | Measure the CG and weight data of each scheme, and optimise the design parameters | 2–3 days | — |
| Phase 4 | Based on the measured feedback, decide whether to proceed with the Scheme D telescopic handle | 5–7 days | 60–100 CNY |

### 11.3 Recommendations for the Next Experiment

1. **Blind test of handle feel**: invite 3–5 participants (with a hand size in the 6–8 cm range) to blindly test handle samples of different circumferences (65/72/80 mm) to determine the optimal circumference.
2. **CG-preference test**: by changing the counterweight rods, have participants perform swing and hitting tests under different CG configurations and record their preferences.
3. **Handle-material friction test**: compare the friction coefficient and feel comfort of three surface treatments—cork sheet, sweat band, and plain-wood varnish.
4. **Handle-detachment durability test**: subject the Scheme B interchangeable interface to ≥100 disassembly/assembly cycles, checking for wear and loosening.

---

## References

[^1]: 国家市场监督管理总局, & 中国国家标准化管理委员会. (2023). *中国成年人人体尺寸* [*Human Dimensions of Chinese Adults*] (GB/T 10000-2023). 中国标准出版社 [Standards Press of China].

[^2]: 国际乒乓球联合会. (2025). *乒乓球比赛规则* [*Laws of Table Tennis*] (Chapter 2). ITTF. https://www.ittf.com/

[^3]: European Patent Office. (2019). *Table Tennis Racket Component* (EP3560560). https://data.epo.org/publication-server/rest/v1.2/patents/EP3560560NWA1/document.html

[^4]: Butterfly Global. (n.d.). *Viscaria Product Page*. https://www.butterfly-global.com/en/products/detail/30041.html

[^5]: NASA. (2010). *Anthropometry and Biomechanics* (NASA-STD-3001). https://www.nasa.gov/analogs/nsrl/standards/anthropometry-and-biomechanics

[^6]: Pheasant, S., & Haslegrave, C. M. (2016). *Bodyspace: Anthropometry, Ergonomics and the Design of Work* (3rd ed.). CRC Press.








