# Formula-EV-CAD-Notes
> 🌐 **Language:** **English** | [🇰🇷 한국어 요약 보기 (Korean)](README_KR.md)

## 📌 Overview
This repository documents my structured learning journey and 3D CAD modeling practice using **3DEXPERIENCE CATIA**, aimed at mechanical packaging and hardware integration for **Formula EV** and **Hybrid Energy Storage Systems (HESS: Battery + Supercapacitor)**.

Rather than only designing electronic circuits, my goal is to bridge **ECAD (Altium Designer)** and **MCAD (3DEXPERIENCE CATIA)** to design robust, FSAE/KSAE-compliant enclosures, cooling brackets, and powertrain mounts.

---

## 🗺️ 4-Phase Learning & Design Roadmap

- [x] **Phase 0:** Repository Setup & Naming Convention Standardization
- [ ] **Phase 1: Part Design Fundamentals (`01_CATIA_Basics/`)**
  - Fully constrained 2D sketching (Green status), `Pad`, `Pocket`, `Hole`, `Shaft`, and `Edge Fillet` operations.
- [ ] **Phase 2: Assembly & Kinematics (`02_Assembly_Kinematics/`)**
  - Multi-part constraints (`Coincidence`, `Contact`, `Offset`) and static/dynamic **Clash Analysis**.
- [ ] **Phase 3: Sheet Metal & Surface Design (`03_Surface_Aero_Practice/`)**
  - Generative Shape Design (GSD) basics for aerodynamic profiles and sheet metal bending for protective covers.
- [ ] **Phase 4: Formula EV & HESS Packaging (`04_Formula_EV_Packaging/`)**
  - Custom aluminum enclosure design for the VCU PCB and HESS module compliant with FSAE EV safety rules.

---

## 📂 Practice Log & Model Gallery

| No. | Folder / Model Name | App (Workbench) | Key Features Practiced | Status |
| :--- | :--- | :--- | :--- | :--- |
| **01** | `01_Bracket_Extrude` | Part Design | Fully constrained sketch, `Pad`, `Pocket`, `Fillet` | 🔄 In Progress |
| **02** | `02_Shaft_Revolve` | Part Design | Axisymmetric profile, `Shaft`, `Groove`, `Chamfer` | ⏳ Planned |
| **03** | `03_Simple_Assembly` | Assembly Design | `Coincidence` & `Contact` constraints, Clash check | ⏳ Planned |

---

## 🛠️ Engineering Standards & File Rules
* **Naming Convention:** Strictly alphanumeric with underscores (e.g., `01_Bracket_v1.stp`) for standardized neutral CAD exchange.
* **Documentation:** Every completed CAD model includes an isometric 3D render (`.png`) showing the **Specification Tree** and a neutral `.stp` file exported from the **3DEXPERIENCE** platform.
