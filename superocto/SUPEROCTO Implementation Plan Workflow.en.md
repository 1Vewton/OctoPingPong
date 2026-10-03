# SUPER O C T O Implementation Plan Workflow

> **Project positioning**: a **parallel technical-exploration branch** of the Octo project, using 3D-printed artificial wood (Wood PLA) and lattice structures to achieve integrated design and rapid iteration of an ultra-light table tennis racket.
> **Rule status**: ❌ non-compliant with ITTF competition rules (see [SUPEROCTO.en > 1 Motivation: Why Is an "Adventure Plan" Needed?](../SUPEROCTO.en.md#1%20Motivation:%20Why%20Is%20an%20"Adventure%20Plan"%20Needed?)); positioned as a training racket, technical prototype, and demonstration project.
> **Overall objective**: within 3–5 iterations, achieve a 3D-printed one-piece racket with a total finished weight of ≤115 g, and evaluate its feel difference from Schemes 1/2/3.

---

## Contents

1. [Overall Roadmap](SUPEROCTO%2520Implementation%2520Plan%2520Workflow.en.md##1-overall-roadmap)
2. [Phase 0: Equipment Readiness and Basic Verification](SUPEROCTO%2520Implementation%2520Plan%2520Workflow.en.md##2-phase-0-equipment-readiness-and-basic-verification)
3. [Phase 1: 3D Model Design and Slicing Parameter Setting](SUPEROCTO%2520Implementation%2520Plan%2520Workflow.en.md##3-phase-1-3d-model-design-and-slicing-parameter-setting)
4. [Phase 2: Material Selection and Print-Parameter Tuning](SUPEROCTO%2520Implementation%2520Plan%2520Workflow.en.md##4-phase-2-material-selection-and-print-parameter-tuning)
5. [Phase 3: Initial Prototype Printing and Feel Evaluation](SUPEROCTO%2520Implementation%2520Plan%2520Workflow.en.md##5-phase-3-initial-prototype-printing-and-feel-evaluation)
6. [Phase 4: Parameter Iteration and Feel Tuning](SUPEROCTO%2520Implementation%2520Plan%2520Workflow.en.md##6-phase-4-parameter-iteration-and-feel-tuning)
7. [Phase 5: Finalising Post-Processing and Durability Testing](SUPEROCTO%2520Implementation%2520Plan%2520Workflow.en.md##7-phase-5-finalising-post-processing-and-durability-testing)
8. [Phase 6: Final Evaluation and Cross-Comparison](SUPEROCTO%2520Implementation%2520Plan%2520Workflow.en.md##8-phase-6-final-evaluation-and-cross-comparison)
9. [Timeline and Milestones](SUPEROCTO%2520Implementation%2520Plan%2520Workflow.en.md##9-timeline-and-milestones)
10. [Risk Contingency Plans](SUPEROCTO%2520Implementation%2520Plan%2520Workflow.en.md##10-risk-contingency-plans)
11. [Appendix: Checklist for Each Phase](SUPEROCTO%2520Implementation%2520Plan%2520Workflow.en.md##11-appendix-checklist-for-each-phase)

---

## 1 Overall Roadmap

```
Phase 0 ──── Phase 1 ──── Phase 2 ──── Phase 3 ──── Phase 4 ──── Phase 5 ──── Phase 6
  │            │            │            │            │            │            │
  │ Equipment  │ 3D model   │ Material   │ Initial    │ Parameter  │ Post-      │ Final
  │ readiness  │ & slicing  │ selection  │ prototype  │ iteration  │ processing │ evaluation
  │ Basic      │ parameters │ Print      │ Feel       │ Feel       │ Durability │ Cross-
  │ validation │            │ tuning     │ evaluation │ tuning     │ testing    │ comparison
  │            │            │            │            │            │            │
  └─────┬──────┘────┬───────┘────┬───────┘────┬───────┘────┬───────┘────┬───────┘
        ↓            ↓            ↓            ↓            ↓            ↓
     [1–2 days]   [2–3 days]   [3–5 days]   [2–3 days]   [5–10 days]  [2–3 days]  [1–2 days]
```

> **Estimated total duration**: 14–28 days (from equipment readiness to final evaluation; some phases can run in parallel)
> **Estimated total material cost**: about 300–500 CNY (including filament, post-processing consumables, and test losses)

---

## 2 Phase 0: Equipment Readiness and Basic Verification

### 2.1 Objectives

- Confirm that the 3D printer is in normal working order and can reliably print Wood PLA material.
- Print standard test coupons to establish a baseline set of printing parameters.
- Become familiar with the printing characteristics of Wood PLA and the basics of post-processing.

### 2.2 Subtasks

| No. | Task | Deliverable | Estimated time |
| :--- | :--- | :----- | :------: |
| 0.1 | Equipment status check and calibration (levelling, extruder cleaning, bed-adhesion test) | Confirmation that the equipment runs normally | 1–2 h |
| 0.2 | Procure Wood PLA filament (eSUN Wood PLA or Amolen Wood PLA recommended, 1 kg) | Filament arrives | 1–3 days (logistics) |
| 0.3 | Print a 20×20×20 mm cube test block (100 % infill) to verify dimensional accuracy and interlayer adhesion | Accuracy measurement data | 1 h |
| 0.4 | Print a 50×50×5 mm thin plate (100 % infill + one of each different infill pattern) to assess surface quality and infill consistency | Infill-pattern comparison samples | 2–3 h |
| 0.5 | Carry out basic post-processing on the test coupons (sanding #120 → #240 → #400) to gain an initial feel for the machinability of Wood PLA | Post-processing experience record | 1 h |
| 0.6 | **Record all printing parameters** (temperature, speed, layer height, flow compensation, etc.) to establish a parameter log | Printing-parameter log (`打印参数日志.md`) | 30 min |

### 2.3 Key Decision Point — Gate 0

| Check item | Pass criterion |
| :----- | :------- |
| Printer accuracy | Measured size deviation of the 20 mm cube ≤ ±0.2 mm |
| Interlayer adhesion | Manual bending of the test coupon does not cause fracture or delamination |
| Wood PLA printing stability | 2 h of continuous printing with no clogging, no stringing, no warping |
| Post-processing feasibility | After sanding the surface is smooth with no obvious layer lines and a genuine wood texture |

> ⚠️ **If Gate 0 is not passed**: troubleshoot the printer problem or change the filament brand; do not proceed to Phase 1.

---

## 3 Phase 1: 3D Model Design and Slicing Parameter Setting

### 3.1 Objectives

- Complete the 3D parametric model design of the table tennis racket (or modify an existing model).
- Determine the slicing strategy (infill pattern, wall thickness, density gradient, printing orientation).
- Output a print-ready G-code file.

### 3.2 Subtasks

| No. | Task | Deliverable | Estimated time |
| :--- | :--- | :----- | :------: |
| 1.1 | **Modelling**: build the 3D model of the racket in CAD software (Fusion 360 / SolidWorks / FreeCAD) | `.stl` / `.step` files | 4–8 h |
| 1.2 | Parametric design (racket-face size, total thickness, handle shape, etc. must be adjustable) to facilitate later iteration | Parametric design file | — |
| 1.3 | Determine the printing orientation (printing the racket face horizontally is recommended, with the Z axis along the thickness direction) | Printing orientation selected | 30 min |
| 1.4 | **Slicing parameter setting** (Orca Slicer / Bambu Studio / Prusa Slicer): | Slicing profile `.3mf` | 2–4 h |
| | — Infill pattern: Gyroid for the racket face, Gyroid for the handle, Triangle for sweet-spot reinforcement | | |
| | — Infill-ratio gradient: racket face 22% → transition zone 22→15% → handle 15% | | |
| | — Wall thickness: 0.6 mm solid layers on the top and bottom faces of the racket face; 0.4 mm all around the handle | | |
| | — Layer height: 0.12 mm for the racket face, 0.20 mm for the handle | | |
| | — Printing speed: 40–50 mm/s | | |
| 1.5 | Estimate the sliced weight and compare it with the theoretical value in [SUPEROCTO.en > 3.3 Weight Estimation](../SUPEROCTO.en.md#3.3%20Weight%20Estimation) | Slice-weight estimate | 15 min |
| 1.6 | Output the V1.0 G-code, ready for printing | `octo_v10.gcode` | 10 min |

### 3.3 Key Points of the Model Design

```
┌──────────────────────────────────┐
│  Racket face (total 4.0 mm)      │
│  ┌───────────────────────────┐    │
│  │ Top solid layer (0.6 mm)   │    │  ← 100% infill, simulates the outer ply
│  ├───────────────────────────┤    │
│  │ Gyroid infill (2.8 mm)     │    │  ← 22% infill, main weight-reduction zone
│  │ ┌─Sweet-spot reinforcement┐    │
│  │ │        Triangle         │    │  ← 35% infill beneath the sweet spot
│  │ └─────────────────────────┘    │
│  ├───────────────────────────┤    │
│  │ Bottom solid layer (0.6mm) │    │  ← 100% infill, bottom face
│  └───────────────────────────┘    │
│  ↕ Gradient transition (5.0 mm)  │
│  ┌───────────────────────────┐    │
│  │ Handle solid skin (0.4 mm all around) │
│  │ ┌─────────────────────────┐│   │
│  │ │   Gyroid core (15%)     ││   │  ← ultra-light handle
│  │ └─────────────────────────┘│   │
│  └───────────────────────────┘    │
└──────────────────────────────────┘
```

> **Parametric variables**: set the racket-face thickness, infill ratio, wall thickness, and sweet-spot reinforcement area as adjustable parameters, so that later iterations only require changing the values and re-slicing, without rebuilding the model.

### 3.4 Key Decision Point — Gate 1

| Check item | Pass criterion |
| :----- | :------- |
| Model integrity | The model is watertight, with no flipped normals and no self-intersecting STL mesh |
| Sliced-weight deviation | Deviation between the sliced estimated weight and the theoretical value ≤ ±5 g |
| Reasonable printing orientation | Minimal or no support structures; sufficient bed-adhesion area |
| Iterable file | Parametric variables are defined and can be modified numerically later |

---

## 4 Phase 2: Material Selection and Print-Parameter Tuning

### 4.1 Objectives

- Compare Wood PLA filaments of different brands/specifications to determine the best material.
- Print standard mechanical test specimens to obtain the material's actual mechanical properties.
- Determine the optimal printing-parameter combination (temperature, speed, layer height, flow compensation).

### 4.2 Subtasks

| No. | Task | Deliverable | Estimated time |
| :--- | :--- | :----- | :------: |
| 2.1 | Prepare 2–3 Wood PLA filament samples (different brands/wood-powder contents) | Filament samples | 2–5 days (logistics) |
| 2.2 | For each filament, print an **interlayer-adhesion test specimen** (ISO 527 dumbbell or a custom flat strip) | Tensile test data | 2–3 h/type |
| 2.3 | For each filament, print a **three-point bending specimen** (80×10×4 mm) to assess bending stiffness and fracture mode | Flexural modulus data | 2 h/type |
| 2.4 | Print a **density-gradient identification sample** (10×10 cm, infill ratio graded from 10% to 40%) to gain a direct feel for the weight–hardness relationship | Feel-identification sample | 3 h |
| 2.5 | Optimise the printing parameters: compare the surface quality at different temperatures (195/200/205/210 °C), layer heights (0.10/0.12/0.16/0.20 mm), and speeds (30/40/50 mm/s) | Optimal parameter combination | 4–6 h |
| 2.6 | **Record all test results** and update the material-parameter database | `材料对比测试记录.md` | 1 h |

### 4.3 Material Comparison Evaluation Matrix

| Evaluation dimension | Weight | Description |
| :------- | :--: | :--- |
| Printing stability | 30% | No clogging, no stringing, no warping, good interlayer adhesion |
| Surface texture | 25% | Authenticity and uniformity of the wood grain after sanding |
| Strength/toughness | 20% | No fracture in three-point bending, no interlayer cracking |
| Price accessibility | 15% | Price per kilogram, ease of purchase |
| Post-processing compatibility | 10% | Ease of sanding, colouring, and oiling |

### 4.4 Key Decision Point — Gate 2

| Check item | Pass criterion |
| :----- | :------- |
| Filament selected | Select the single filament with the highest overall score and use it throughout |
| Printing-parameter window | Determine the temperature, speed, and layer-height combination that guarantees 10 h of continuous printing without failure |
| Density–hardness relationship data | Obtain a predictable relationship curve between infill ratio and bending stiffness |

---

## 5 Phase 3: Initial Prototype Printing and Feel Evaluation

### 5.1 Objectives

- Print the V1.0 initial prototype blade (parameters set according to [SUPEROCTO.en > 3.2 Parameter Table](../SUPEROCTO.en.md#3.2%20Parameter%20Table)).
- Complete basic post-processing (sanding + oiling).
- Carry out a subjective feel evaluation and record qualitative feedback.
- Attach test rubbers, weigh the total finished weight, and measure the centre-of-gravity position.

### 5.2 Subtasks

| No. | Task | Deliverable | Estimated time |
| :--- | :--- | :----- | :------: |
| 3.1 | Print the V1.0 blade (estimated 6–8 h) | Printed blade blank | 6–8 h |
| 3.2 | Basic post-processing: sanding #120 → #240 → #400 → wood wax oil / matte varnish, 2 coats | Post-processed blade | 2 h (in two sessions) |
| 3.3 | Weigh (bare blade), record the actual weight, and compare it with the slice estimate/theoretical value | Actual weight data | 10 min |
| 3.4 | Measure the centre-of-gravity position (measured from the end of the handle) | CG-position data | 10 min |
| 3.5 | Attach test rubbers (identical rubbers on both sides; cut-off old rubbers or inexpensive training rubbers recommended) | Playable racket | 30 min |
| 3.6 | **Subjective feel evaluation**: | Feel-evaluation record | 1–2 h |
| | — Grip comfort (handle size, CG position) | | |
| | — Shadow-swing feel (swing inertia, head-heavy/head-light feel) | | |
| | — Wall-hitting or ball-machine test (rebound feel, sound, sweet-spot response) | | |
| 3.7 | Qualitative comparison with the expected feel of Schemes 1/2/3 in [Three Blade Design Schemes and Procurement List](../%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Three%20Blade%20Design%20Schemes%20and%20Procurement%20List.en.md) | Preliminary cross-comparison | 30 min |
| 3.8 | Record all findings and update the iteration-requirements list | Iteration-requirements list | 30 min |

### 5.3 Feel-Evaluation Indicators

| Evaluation item | Evaluation method | Recording method |
| :------- | :------- | :------- |
| **Overall weight feel** | Shadow swing + wall hitting, compared with a conventional racket | Score 1–5 + textual description |
| **Grip comfort** | Hold continuously for 5 min and assess fatigue | Score 1–5 + textual description |
| **Hitting feel** | Hit against a wall 50 times, sensing rebound force and vibration | Hard/soft/moderate + textual description |
| **Sweet-spot size** | Tap point by point to sense the sweet-spot distribution | Estimated sweet-spot diameter (mm) |
| **Sound feedback** | Racket sound on impact (crisp/muffled) | Textual description |
| **CG feel** | Shadow swing + forehand/backhand switching | Head-heavy/balanced/head-light judgement |

### 5.4 Key Decision Point — Gate 3

| Check item | Pass criterion |
| :----- | :------- |
| Blade usable normally | No structural defects (cracking, delamination, deformation) |
| Weight as expected | Actual bare-blade weight ≤ 55 g (deviation ≤ ±3 g) |
| Acceptable CG position | CG ≤ 120 mm from the end of the handle |
| Comfortable handle size | Handle circumference ≤ 80 mm, length ≤ 70 mm (refer to [Hand-Size and Grip-Strength Study of Dwarfism Patients](../%E9%98%B6%E6%AE%B51-%E5%89%8D%E7%BD%AE%E5%87%86%E5%A4%87/Research%20Report%20on%20Hand-Size%20and%20Grip-Strength%20of%20Dwarfism%20Patients.en.md)) |

> ⚠️ **If Gate 3 is not passed**: depending on the specific problem, return to Phase 1 (model modification) or Phase 2 (parameter adjustment).

---

## 6 Phase 4: Parameter Iteration and Feel Tuning

### 6.1 Objectives

- Formulate a parameter-adjustment strategy based on the Phase-3 feel feedback.
- Print 2–4 parameter-variant versions (different infill ratios, wall thicknesses, sweet-spot designs).
- Carry out comparative feel evaluation and lock in the optimal parameter combination.
- If possible, invite users (patients with dwarfism) to take part in the subjective evaluation.

### 6.2 Parameter-Adjustment Strategy

Following the recommendations in [SUPEROCTO.en > 6 Feel Tuning of the Lattice Structure](../SUPEROCTO.en.md#6%20Feel%20Tuning%20of%20the%20Lattice%20Structure), the following tuning route is recommended:

#### Tuning direction 1: hardness adjustment

| Version | Infill ratio | Solid-layer thickness | Estimated weight change | Expected feel |
| :--- | :----: | :------: | :----------: | :------- |
| V1.0 (baseline) | 22% | 0.6 mm | — | Baseline reference |
| V1.1 (soft version) | 18% | 0.5 mm | −4~5 g | Softer, more vibration-absorbing |
| V1.2 (hard version) | 28% | 0.7 mm | +5~6 g | Harder, stronger rebound |

#### Tuning direction 2: centre-of-gravity adjustment

| Version | Handle infill ratio | Racket-face infill ratio | Direction of CG change |
| :--- | :--------: | :--------: | :----------- |
| V1.0 | 15% | 22% | Baseline |
| V2.0 (head-light) | 20% | 18% | Moves ~5 mm towards the handle |
| V2.1 (head-heavy) | 10% | 25% | Moves ~5 mm towards the racket head |

#### Tuning direction 3: sweet-spot optimisation

| Version | Sweet-spot reinforcement area | Reinforcement infill ratio | Effect |
| :--- | :----------: | :--------: | :--- |
| V1.0 | 40 mm diameter | 35% | Baseline |
| V3.0 | 30 mm diameter | 40% | More concentrated sweet spot |
| V3.1 | 50 mm diameter | 30% | Larger sweet spot |

### 6.3 Subtasks

| No. | Task | Deliverable | Estimated time |
| :--- | :--- | :----- | :------: |
| 4.1 | Based on the Gate 3 feedback, set the priority of the tuning directions | Tuning plan | 30 min |
| 4.2 | Modify the slicing parameters and generate the G-code for 2–4 variant versions | Variant G-code files | 1–2 h |
| 4.3 | Print each variant version one by one (note the printing order: print the version most likely to succeed first) | Blade blank of each version | 6–8 h/version |
| 4.4 | Post-process each version (unified sanding process to ensure a fair comparison) | Post-processed blade of each version | 1 h/version |
| 4.5 | **Double-blind feel test**: label the version numbers and have the evaluator rank them blindly | Feel ranking + comments | 1–2 h |
| 4.6 | Determine the final parameter combination and generate the V-final G-code | `octo_vfinal.gcode` | 30 min |

### 6.4 Key Decision Point — Gate 4

| Check item | Pass criterion |
| :----- | :------- |
| Satisfactory feel | Subjective feel score ≥ 4/5 (compared with the expected feel of Scheme 1) |
| Weight target met | Blade weight ≤ 50 g (≤ 55 g if the handle is included); total finished weight ≤ 120 g |
| Reproducibility | Printing the same G-code twice gives a weight deviation ≤ ±1 g |
| Clear sweet spot | The sweet-spot range can be identified by the tapping method, with a diameter ≥ 30 mm |

---

## 7 Phase 5: Finalising Post-Processing and Durability Testing

### 7.1 Objectives

- Determine the final post-processing process flow (sanding-grit sequence, coating type and number of coats).
- Carry out durability testing (simulating the impacts, knocks, and humid environments of daily use).
- Evaluate long-term reliability (risk of interlayer delamination, surface wear, moisture-absorption effects).

### 7.2 Subtasks

| No. | Task | Deliverable | Estimated time |
| :--- | :--- | :----- | :------: |
| 5.1 | Compare the effects of different post-processing schemes (wood wax oil vs. polyurethane varnish vs. epoxy coating) on surface hardness and texture | Coating-comparison samples | 2 h + 24 h curing wait |
| 5.2 | **Drop test**: free-drop from a height of 1 m onto a hard floor 10 times and check structural integrity | Drop-test report | 30 min |
| 5.3 | **Edge-impact test**: lightly strike the racket edge with a mallet 20 times to assess edge knock resistance | Edge-impact test report | 15 min |
| 5.4 | **Moisture-absorption test**: weigh, then place in a 50% RH environment for 24 h and weigh again to assess the moisture-absorption rate | Moisture-absorption data | 24 h |
| 5.5 | **Interlayer fatigue test**: repeatedly bend the blade (amplitude 10 mm, frequency 1 Hz, 100 cycles) and check for interlayer cracking | Fatigue-test report | 30 min |
| 5.6 | Determine the final post-processing process specification and output a standard operating procedure (SOP) | `后处理SOP.md` | 1 h |
| 5.7 | Produce the final-version blade (using the post-processing SOP) | Final-version blade | 6–8 h printing + post-processing |

### 7.3 Durability Pass Criteria

| Test item | Pass criterion |
| :------- | :------- |
| Drop test | No visible cracks, no delamination, weight change ≤ ±0.5 g |
| Edge impact | Edge indentation ≤ 0.5 mm, no through cracks |
| Moisture-absorption rate | 24 h weight gain ≤ 1.5% (coating protection adequate) |
| Interlayer fatigue | After 100 bending cycles, no abnormal noise and no visible delamination |

> ⚠️ **If the durability test is not passed**: strengthen the surface coating or adjust the printing parameters (increase the wall thickness, raise the bed temperature to improve interlayer adhesion).

---

## 8 Phase 6: Final Evaluation and Cross-Comparison

### 8.1 Objectives

- Compare the performance of Scheme 4 (SUPER OCTO) with Schemes 1/2/3 in all dimensions.
- Write the final evaluation report, clarifying the applicable scenarios and limitations of Scheme 4.
- Archive all design files, printing parameters, and test data to form a reproducible knowledge base.

### 8.2 Subtasks

| No. | Task | Deliverable | Estimated time |
| :--- | :--- | :----- | :------: |
| 6.1 | Compare one-to-one against the scheme parameters in [Three Blade Design Schemes and Procurement List](../%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Three%20Blade%20Design%20Schemes%20and%20Procurement%20List.en.md) | Cross-comparison table | 1 h |
| 6.2 | Summarise the test data from all phases (weight, CG, hardness, durability) | Consolidated data table | 1 h |
| 6.3 | Write the SUPER OCTO summary report, covering: | `SUPEROCTO总结报告.md` | 2–3 h |
| | — Conclusion on technical feasibility | | |
| | — Final weight and performance data | | |
| | — Summary of the feel evaluation | | |
| | — Cost analysis (equipment + materials + time) | | |
| | — Comparison conclusion with Schemes 1/2/3 | | |
| | — Recommendations on applicable scenarios | | |
| | — Future improvement directions | | |
| 6.4 | Archive all design files, G-code, printing-parameter logs, and test records | Archive folder | 30 min |
| 6.5 | Update the project README.md to add the conclusions on Scheme 4 | Updated README.md | 30 min |

### 8.3 Cross-Comparison Evaluation Matrix

| Comparison dimension | Scheme 1 (3-ply all-wood) | Scheme 2 (5-ply all-wood) | Scheme 3 (5+2 fibre) | Scheme 4 (3D-printed) |
| :------- | :---------------: | :---------------: | :---------------: | :--------------: |
| **Total finished weight (g)** | 111–119 | 118–125 | 119–126 | **target ≤115** |
| **ITTF compliance** | ✅ | ✅ | ✅ | ❌ |
| **Material cost (CNY)** | 50–80 | 70–100 | 100–180 | **10–18 / blade** |
| **Design freedom** | ★★ | ★★ | ★★★ | **★★★★★** |
| **Iterability** | Low | Low | Medium | **Extremely high** |
| **Feel** | Traditional all-wood | Advanced all-wood | Fibre composite | **Lattice (to be evaluated)** |
| **Fabrication difficulty** | ★☆☆☆☆ | ★★☆☆☆ | ★★★★☆ | **★★★☆☆** |

### 8.4 Final Decision

| Decision option | Description |
| :------- | :--- |
| **Scheme 4 feasible, recommended for use** | Scheme 4 has significant advantages in weight, design freedom, and iteration efficiency, with acceptable feel; recommended for training/recreation |
| **Scheme 4 feasible but with poor feel** | Scheme 4 is technically verified but its feel differs considerably from natural wood; to be used selectively in combination with Schemes 1/2/3 |
| **Scheme 4 verification failed** | It cannot meet expectations on key indicators; abandon the Scheme-4 route and revert to Schemes 1/2/3 |

---

## 9 Timeline and Milestones

```
Week 1          Week 2          Week 3          Week 4
├───┬───┬───┬───┼───┬───┬───┬───┼───┬───┬───┬───┼───┬───┬───┬───┤
│   Phase 0      │   Phase 1      │   Phase 2      │   Phase 3      │
│ Equipment      │ Modelling &    │ Material       │ Initial        │
│ readiness      │ slicing        │ tuning         │ prototype      │
└───▼───┴───────┴───┴───▼───┴───┴───┴───▼───┴───┴───┴───▼───┴───┘
    ▲              ▲              ▲              ▲
    │ Gate 0       │ Gate 1       │ Gate 2       │ Gate 3
    │              │              │              │
    └──── Parallel ─┴─────────────┘

Week 5          Week 6
├───┬───┬───┬───┼───┬───┬───┬───┤
│   Phase 4      │   Phase 5+6    │
│ Parameter      │ Durability +   │
│ iteration      │ summary        │
└───▼───┴───────┴───▼───┴────────┘
    ▲              ▲
    │ Gate 4       │ Project complete
    │              │
```

### 9.1 Key Milestones

| Milestone | Estimated time point | Deliverable |
| :----- | :----------: | :----- |
| **M0** — Equipment ready | Day 1–3 | Printer calibration complete, test coupons printed successfully |
| **M1** — Modelling complete | Day 4–7 | Parametric 3D model + slicing profile |
| **M2** — Material selected | Day 5–10 (parallel with M1) | Material-comparison test report + optimal parameter combination |
| **M3** — Initial prototype | Day 11–14 | V1.0 blade + feel-evaluation record |
| **M4** — Parameters locked | Day 15–21 | Final parameter combination + V-final G-code |
| **M5** — Project complete | Day 22–28 | Final blade + summary report + complete archive |

---

## 10 Risk Contingency Plans

### 10.1 Technical Risks

| Risk | Probability | Impact | Contingency |
| :--- | :--: | :--: | :--- |
| **Wood PLA clogging/print failure** | Medium | High | ① Switch to a larger nozzle (0.6 mm) to reduce clogging risk ② Keep filament of another brand on hand ③ Dry the filament before printing (Wood PLA absorbs moisture easily) |
| **Interlayer delamination** | Medium | High | ① Increase the wall thickness (4 shells → 6 shells) ② Raise the bed temperature (60→70 °C) to improve interlayer adhesion ③ Adjust the printing orientation so that the principal-stress direction is parallel to the layer plane |
| **Warping/deformation** | Medium | Medium | ① Use a Brim (8 mm) ② Use an enclosure or a draught shield ③ Lower the printing speed |
| **Dimensional deviation (handle too tight/loose)** | Low | Medium | ① Check flow compensation before printing ② Print a fit-test ring (print only a small sample of the handle cross-section to check the dimensions) |
| **Unacceptable lattice feel** | Medium | High | ① Print a feel-identification sample in Phase 2 for early assessment ② Try hybrid manufacturing (3D-printed core + hot-pressed natural-wood veneer) |

### 10.2 Schedule Risks

| Risk | Impact | Contingency |
| :--- | :--: | :--- |
| **Printer breakdown (long repair)** | High | ① Prepare a backup printing option (contact the school or a makerspace) ② Or pause Scheme 4 and prioritise Schemes 1/2/3 |
| **Filament procurement delay** | Medium | ① Order in advance, allowing 5–7 days of logistics margin ② Choose fast logistics channels such as Taobao/JD.com |
| **Feel evaluation needs more iterations** | Medium | ① Phase 4 has a margin for 2–4 iterations ② An additional Phase 4b (extra iterations) can be added after Phase 4 |

### 10.3 Exit Conditions

If any of the following conditions is met, **Scheme 4 should be terminated** and resources concentrated on Schemes 1/2/3:

1. **The weight of the Phase-3 initial prototype > 60 g**, and it cannot be reduced below 55 g through parameter optimisation.
2. **The total Phase-3 feel-evaluation score < 2/5**, with no clear direction for tuning improvement.
3. **Three consecutive printing failures** (clogging, warping, delamination, etc.) that cannot be resolved by parameter adjustment.
4. **Printer repair time > 2 weeks**, with no alternative printing equipment available.

---

## 11 Appendix: Checklist for Each Phase

### Phase 0 Checklist

- [ ] 3D printer calibrated (levelling, Z-axis offset)
- [ ] Wood PLA filament has arrived (at least 1 spool)
- [ ] 20 mm cube test coupon printed successfully (size deviation ≤ ±0.2 mm)
- [ ] 50×50 mm infill-comparison coupon printed
- [ ] Basic post-processing operation completed (sanding experience)
- [ ] Printing-parameter log established
- [ ] **Gate 0 passed**: may proceed to Phase 1

### Phase 1 Checklist

- [ ] 3D model completed (racket face + handle integrated)
- [ ] Model parameterised (thickness, infill ratio, sweet-spot area, etc. adjustable)
- [ ] Printing orientation determined (racket face horizontal)
- [ ] Slicing profile completed (infill pattern, infill-ratio gradient, wall thickness, layer height)
- [ ] Sliced estimated weight compared with the theoretical value (deviation ≤ ±5 g)
- [ ] G-code V1.0 output
- [ ] **Gate 1 passed**: may proceed to Phase 2

### Phase 2 Checklist

- [ ] At least 1 Wood PLA filament has completed the printing-stability test
- [ ] Interlayer-adhesion test specimen completed and data recorded
- [ ] Three-point bending specimen completed and data recorded
- [ ] Density-gradient identification sample printed
- [ ] Optimal printing-parameter combination determined (temperature, speed, layer height)
- [ ] Material-comparison test record archived
- [ ] **Gate 2 passed**: may proceed to Phase 3

### Phase 3 Checklist

- [ ] V1.0 blade printed
- [ ] Basic post-processing completed
- [ ] Actual bare-blade weight recorded (≤ 55 g)
- [ ] CG-position measurement recorded (≤ 120 mm from the end of the handle)
- [ ] Test rubbers attached
- [ ] Subjective feel-evaluation record completed
- [ ] Iteration-requirements list compiled
- [ ] **Gate 3 passed**: may proceed to Phase 4

### Phase 4 Checklist

- [ ] Tuning plan formulated (based on Phase-3 feedback)
- [ ] G-code generated for 2–4 variant versions
- [ ] Each version printed and post-processed
- [ ] Double-blind feel test completed and ranked
- [ ] Final parameter combination determined
- [ ] V-final G-code output
- [ ] **Gate 4 passed**: may proceed to Phase 5

### Phase 5 Checklist

- [ ] Post-processing scheme comparison completed (final coating selected)
- [ ] Drop test passed (10 times, no cracks, no delamination)
- [ ] Edge-impact test passed (20 times, indentation ≤ 0.5 mm)
- [ ] Moisture-absorption test passed (24 h weight gain ≤ 1.5%)
- [ ] Interlayer fatigue test passed (100 bending cycles, no delamination)
- [ ] Post-processing SOP document completed
- [ ] Final-version blade produced

### Phase 6 Checklist

- [ ] Cross-comparison table completed (Scheme 4 vs Schemes 1/2/3)
- [ ] Consolidated data table completed
- [ ] Summary report written
- [ ] All design files, G-code, and test records archived
- [ ] README.md update completed
- [ ] **Project complete**

---

## References

The technical reference information in this plan workflow is drawn entirely from the following internal project documents:

- [SUPER OCTO](../SUPEROCTO.en.md) — Scheme-4 technical design document (core reference)
- [Three Blade Design Schemes and Procurement List](../%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Three%20Blade%20Design%20Schemes%20and%20Procurement%20List.en.md) — Schemes 1/2/3 design parameters (cross-comparison baseline)
- [Hand-Size and Grip-Strength Study of Dwarfism Patients](../%E9%98%B6%E6%AE%B51-%E5%89%8D%E7%BD%AE%E5%87%86%E5%A4%87/Research%20Report%20on%20Hand-Size%20and%20Grip-Strength%20of%20Dwarfism%20Patients.en.md) — basis for handle-size design
- [Lightweight Material Density and Price Survey](../%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Research%20Report%20on%20Density%20and%20Price%20of%20Lightweight%20Table%20Tennis%20Racket%20Materials.en.md) — material-selection reference
- [Slim-Handle and Adjustable Handle Design Report](../%E9%98%B6%E6%AE%B52-%E8%B0%83%E7%A0%94%E4%BB%A5%E5%8F%8A%E6%9D%90%E6%96%99%E5%87%86%E5%A4%87/Design%20Report%20on%20Slim-Handle%20and%20Adjustable%20Counterweight%20and%20Length%20Handles.en.md) — handle-design reference
- [Wood and Fiber Material Performance Test Plan](../%E9%98%B6%E6%AE%B53-%E5%AE%9E%E9%AA%8C%E4%B8%8E%E6%B5%8B%E8%AF%95/Wood%20and%20Fibre%20Material%20Performance%20Test%20Plan.en.md) — reference for mechanical-test methods
- [Standard Racket Technical Baseline](../%E9%98%B6%E6%AE%B51-%E5%89%8D%E7%BD%AE%E5%87%86%E5%A4%87/Standard%20Table%20Tennis%20Racket%20Technical%20Parameter%20Baseline%20Report.en.md) — baseline comparison data






