# Industrial Grain & Seed Destoner – 3D CAD & Mechanical Design


## 📌 Project Overview
This repository contains the complete 3D CAD design, component modeling, and full mechanical assembly of an **Industrial Grain and Seed Destoner Machine**, developed using **SolidWorks**. 

In agricultural processing, destoning is a vital pre-milling stage used to remove high-density foreign contaminants—such as stones, glass, metal fragments, and soil clods—from grains and seeds. This project demonstrates the practical design of an industrial-grade separation machine integrating **Induction Fan**, **vibro Motors**, and **structural vibration isolation**.

---

## 🛠️ Machine Architecture & Design Features


### 1. Induction fan duct system & Vibratory Deck (`deck.SLDPRT`, `mesh.SLDPRT`)
* **Inclined Multi-Layer Screen:** Designed with replaceable woven wire screens angled to optimize material residence time and separation efficiency.
* **Structural Support:** Internal array of transverse tubular cross-members engineered to resist cyclic fatigue from continuous vibration.

### 2. Vibratory Drive & Isolation System (`frame.SLDPRT`)
* **Dual vibro Motors:** Configured for counter-rotating linear oscillation, imparting a directional throw vector to propel heavy stones upward against the deck's incline.
* **Spring Dampers:** Heavy-duty helical coil springs mounted at the four chassis corners isolate dynamic reaction forces, preventing structural fatigue in surrounding plant equipment.

### 3. Aspiration & Air sucking System (`fan.SLDPRT`, `duct.SLDPRT`)
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
│
├── drawings/                      


# Author
Abel Addis