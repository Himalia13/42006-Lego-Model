<!--
Licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0).
LEGO® is a registered trademark of the LEGO Group, which does not sponsor, authorize, or endorse this project.
-->

# LEGO Technic 42006 Excavator CAD Model

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](LICENSE.md)
[![Institution](https://img.shields.io/badge/Institution-UC3M-blue.svg)](https://www.uc3m.es/)
[![Degree](https://img.shields.io/badge/Degree-Aerospace%20Engineering-orange.svg)](#course-information)
[![Software](https://img.shields.io/badge/CAD-Universal%20%2F%20Solid%20Edge-red.svg)](#requirements)
[![Render](https://img.shields.io/badge/3D-Blender-yellow.svg)](https://www.blender.org/)
[![GitHub Stars](https://img.shields.io/github/stars/Himalia13/42006-Lego-Model?style=social)](https://github.com/Himalia13/42006-Lego-Model/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/Himalia13/42006-Lego-Model)](https://github.com/Himalia13/42006-Lego-Model/commits/main)

<p align="center">
  <img width="800" src="Renders/Total.jpg" alt="LEGO Technic 42006 Excavator Render" />
</p>

A complete, high-precision 3D CAD modeling project of the official **LEGO Technic 42006 Excavator** set. Developed as part of the *Graphic Design in Aerospace Engineering* curriculum at **Universidad Carlos III de Madrid (UC3M)**.

All individual components, subassemblies, composite parts, technical drawings, and converted formats (`.STL`, `.OBJ`, `.FBX`, `.STEP`, etc.) are organized natively in dedicated folders for seamless exploration, 3D printing, and Blender visualization.

---

### Quick Navigation

[**Project Overview**](#project-overview) |
[**Repository Structure**](#repository-structure) |
[**Supported Formats**](#supported-formats) |
[**Requirements & Software**](#requirements) |
[**Visual Showcase**](#visual-showcase) |
[**How to Use**](#how-to-use) |
[**Course Details**](#course-information) |
[**License & Disclaimer**](#license--disclaimer)

---

## Project Overview

The **LEGO Technic 42006 Excavator** features complex mechanical movements including a 360° rotating superstructure, an articulated boom/arm, and a functional four-prong grabber. 

Key engineering objectives of this repository:
- **Precision Modeling:** Recreate every individual piece and mechanical linkage in **Solid Edge**.
- **Engineering Documentation:** Draft standardized technical drawings and dimensioned sheets (`Drafts/`).
- **3D Printing Readiness:** Export optimized mesh geometry for additive manufacturing slicers (`STL/`, `3MF/`).
- **Visualization & Animation:** Export clean models (`OBJ/`, `FBX/`) for lighting, texturing, and dynamic physics in **Blender**.

---

## Repository Structure

.
├── Assembly/          # Main mechanical assembly and subassemblies (.asm)
├── Parts/             # Individual component models (.par)
├── Composite_Parts/   # Complex multi-part sub-assemblies
├── Drafts/            # Dimensioned technical engineering drawings (.pdf)
├── Renders/           # High-resolution image renders (.png, .jpg) & animations (.mp4, .gif)
├── STL/               # Standard Triangle Language files for 3D printing
├── OBJ/               # Wavefront 3D mesh files
├── FBX/               # Filmbox 3D exchange files
├── STEP/              # ISO 10303 universal CAD exchange files
└── Resources/         # Reference materials, textures, and asset files


---

## Supported Formats

The repository includes native CAD files along with universal exchange formats:

`.PAR` • `.ASM` • `.STEP` • `.IGES` • `.STL` • `.3MF` • `.OBJ` • `.FBX` • `.PDF` • `.JT` • `.SAT` • `.U3D` • `.X_B`

---

## Requirements

To view, edit, or utilize the assets in this repository:

* **CAD Modeling & Editing:** 
  * **Any CAD Software** (Fusion 360, SolidWorks, Inventor, FreeCAD, CATIA, etc.): You can open, edit, and inspect the model geometry using the universal `.STEP` and `.IGES` files located in the `STEP/` folder.
  * **Siemens Solid Edge:** Required **only** if you wish to inspect or modify the original parametric feature tree, native constraints, or `.par` / `.asm` file structures.
* **3D Printing:** Any modern slicer (Bambu Studio, PrusaSlicer, Cura) accepting `.stl` or `.3mf` files.
* **Rendering & Animation:** Blender 3.0+ or any 3D software capable of importing `.obj` or `.fbx` formats.
* **Documentation:** Any standard PDF reader for files in `Drafts/`.

---

## Visual Showcase

### High-Resolution Render
<p align="center">
  <img src="Renders/Total.jpg" alt="Excavator Full Assembly Render" width="750" />
</p>

### Technical Engineering Drawing
<p align="center">
  <img src="Resources/Gray_4566742_AVV-1.png" alt="Engineering Technical Drawing Sample" width="750" />
</p>

---

## How to Use

### 1. Clone the Repository

git clone [https://github.com/Himalia13/42006-Lego-Model.git](https://github.com/Himalia13/42006-Lego-Model.git)
2. CAD Workflows
Universal CAD: Import .step files from STEP/ into any CAD suite to edit geometry or create custom assemblies.

Solid Edge: Open native .asm files located in Assembly/ to edit parametric features and native assembly relationships directly via Parts/.

3. Additive Manufacturing (3D Printing)
Import .stl or .3mf files into your preferred slicer.

Recommended settings: 0.2mm layer height, 15-20% infill, PLA/PETG material.

4. Rendering & Animation (Blender)
Import .obj or .fbx files into Blender.

Materials and mechanical pivots are set up for visualization and animation.

Course Information
Institution: Universidad Carlos III de Madrid (UC3M)

Degree: Bachelor's Degree in Aerospace Engineering

Subject: Graphic Design

Academic Year: 2023–2024

License & Disclaimer
This repository and its assets are licensed under the Creative Commons Attribution-NonCommercial 4.0 International License. See the full terms in the LICENSE.md file.

Disclaimer
LEGO® is a registered trademark of the LEGO Group of companies, which does not sponsor, authorize, or endorse this repository. This project is an independent educational fan creation.