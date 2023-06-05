# Gerbers

Include the Gerber files for {{cookiecutter.project_name}} in this section. These files are used for PCB fabrication.

## Required Gerber Files

Ensure that the following Gerber files are included for manufacturing {{cookiecutter.project_name}}:

- Copper Layers: `projectname.GTL`, `projectname.GBL` (top and bottom copper layers)
- Silk Layers: `projectname.GTO`, `projectname.GBO` (top and bottom silkscreen layers)
- Solder Paste Layers: `projectname.GTP`, `projectname.GBP` (top and bottom solder paste layers)
- Mask Layers: `projectname.GTS`, `projectname.GBS` (top and bottom solder mask layers)
- Drill Files: `projectname.TXT` or `projectname.XLN` (NC drill file)
- Board Outline: `projectname.GML` or `projectname.GKO` (board outline or edge cuts)

Please ensure that you generate or provide the appropriate Gerber files with the correct extensions for your PCB fabrication. These files are necessary for accurate manufacturing of the PCB.

