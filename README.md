# Industrial Grain & Seed Destoner – 3D CAD & Mechanical Design

![Destoner CAD Assembly](1000018983.jpg)

## 📌 Project Overview
This repository contains the complete 3D CAD design, component modeling, and full mechanical assembly of an **Industrial Grain and Seed Destoner Machine**, developed using **SolidWorks**. 

In agricultural processing, destoning is a vital pre-milling stage used to remove high-density foreign contaminants—such as stones, glass, metal fragments, and soil clods—from grains and seeds. This project demonstrates the practical design of an industrial-grade separation machine integrating **pneumatic fluidization**, **vibratory material transport**, and **structural vibration isolation**.

---

## 🛠️ Machine Architecture & Design Features

![Exploded View](1000019010.jpg)

### 1. Fluidization Bed & Vibratory Deck (`deck.SLDPRT`, `mesh.SLDPRT`)
* **Inclined Multi-Layer Screen:** Designed with replaceable woven wire screens angled to optimize material residence time and separation efficiency.
* **Structural Support:** Internal array of transverse tubular cross-members engineered to resist cyclic fatigue from continuous vibration.

### 2. Vibratory Drive & Isolation System (`frame.SLDPRT`)
* **Dual Eccentric Motors:** Configured for counter-rotating linear oscillation, imparting a directional throw vector to propel heavy stones upward against the deck's incline.
* **Spring Dampers:** Heavy-duty helical coil springs mounted at the four chassis corners isolate dynamic reaction forces, preventing structural fatigue in surrounding plant equipment.

### 3. Aspiration & Pneumatic System (`fan.SLDPRT`, `duct.SLDPRT`)
* **Centrifugal Blower:** Base-mounted fan unit providing continuous upward airflow through the mesh bed to fluidize lighter grain kernels.
* **Power Transmission:** Powered by a standard electric motor via a V-belt and pulley setup.
* **Dust Control:** Integrated overhead hood and vertical ducting capture light chaff and dust.

### 4. Feed Hopper & Frame Assembly (`hopper.SLDPRT`)
* Free-standing structural frame housing an elevated conical feed hopper with a adjustable slide-gate to regulate mass flow rate into the deck.

---

## 📂 Repository File Structure

```text
.
├── assembly/
│   └── destoner real assembly.SLDASM    # Master SolidWorks assembly file
├── parts/
│   ├── frame.SLDPRT                      # Base chassis and spring mounting plates
│   ├── deck.SLDPRT                       # Oscillating screen bed housing
│   ├── mesh.SLDPRT                       # Woven wire screen deck
│   ├── fan.SLDPRT                        # Centrifugal blower & impeller
│   ├── duct.SLDPRT                       # Pneumatic extraction ducting & hood
│   └── hopper.SLDPRT                     # Feed hopper & elevated support structure
├── documentation/
│   └── destoner_project_report.tex       # Complete LaTeX technical report
└── images/
    ├── 1000018983.jpg                    # Full assembly render
    └── 1000019010.jpg                    # Exploded assembly view

# Author
Abel Addis