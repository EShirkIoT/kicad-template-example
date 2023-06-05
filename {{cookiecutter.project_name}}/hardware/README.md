# {{cookiecutter.project_name}} KiCAD Design Files

This repository contains the KiCAD design files for {{cookiecutter.project_name}}. This README provides instructions on using the automated project creation and utilizing specific KiCAD plugins for an efficient workflow.

## Prerequisites

Before starting, ensure you have the following software and plugins installed:

- KiCAD 7: [Download KiCAD](https://kicad.org/download/)
- Interactive Html Bom (iBOM) Plugin: Available via the KiCAD Plugin Manager. Generates an interactive Bill of Materials (BoM) and provides component placement visualization.
- KiKit Plugin: Available via the KiCAD Plugin Manager. Enables PCB panelization, optimizing the layout for production and maximizing PCB utilization.
- Archive 3D models Plugin: Available via the KiCAD Plugin Manager. Consolidates and maps 3D models in one place for accurate component placement visualization.
- JLC PCB Fabrication Toolkit Plugin: Available via the KiCAD Plugin Manager. One-click generation of Gerber files, BoM, and Pick and Place files, streamlining the transition from design to production.
- Freerouting Plugin: Available via the KiCAD Plugin Manager. Optional autorouting tool for PCB layout, though manual routing is recommended for optimal control and signal integrity.
- JLC2KiCAD_lib by TousstNicolas: Available via the KiCAD Plugin Manager. Script to convert components from EasyEDA, JLC, or LCSC formats to KiCAD format.

## Getting Started

Follow these steps to utilize the automated project creation and KiCAD plugins for an efficient workflow:

1. Use your project template to create the {{cookiecutter.project_name}} project, including the schematic and PCB templates, grids, DRC settings, and library mappings.
2. Open the project in KiCAD.
3. Utilize the Interactive Html Bom (iBOM) plugin to generate an interactive Bill of Materials (BoM) and visualize component placement.
4. Use the KiKit plugin for PCB panelization, optimizing the layout for production and maximizing PCB utilization.
5. Utilize the Archive 3D models plugin to consolidate and map 3D models in one place, ensuring accurate component placement visualization.
6. Use the JLC PCB Fabrication Toolkit plugin to generate Gerber files, BoM, and Pick and Place files in a single click, facilitating an efficient transition from design to production.
7. If desired, utilize the Freerouting plugin for autorouting, though it's recommended to consider manual routing for optimal control and signal integrity.
8. Optionally, utilize the JLC2KiCAD_lib by TousstNicolas script to convert components from EasyEDA, JLC, or LCSC formats to KiCAD format.