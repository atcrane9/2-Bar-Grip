# 2-Bar-Grip

The 2 Bar Grip is a tool used to stabilize [metal rods](https://www.homedepot.com/pep/Everbilt-3-16-in-x-3-ft-Plain-Steel-Solid-Round-Rod-0403/332733428) (diameter: 4.76 mm (3/16 in)) at 3.5 cm apart for use with the balance beam motor task. The tool has both a 5.5mm and an 8mm hook in order to hang from the inside of either a 75Jag Cage (Allentown) or a N10 Mouse cage (Ancare).
<p>
    <img src=Images/2BarGrip1.jpg height="290"> <img src=Images/2BarGripSetup2.jpg height="290"> <img src=Images/HookDimensions.jpg height="290">
   </p>
<p>
    <img src=Images/Example2.jpg height="290">
   </p>

The link to the paper that commissioned this tool can be found here -> DOI: [10.1126/sciadv.adw7427](h ttps://doi.org/10.1126/sciadv.adw7427)

## Hardware

All files were printed using a Prusa i3 MKS3 with a 0.6mm nozzle, using OVERTURE PLA Plus (PLA+) 1.75mm Professional Toughness filament.\
Painter's tape was put on print bed to increase print adhesion with bed.
* Make sure tape is completely flat
* No gaps between tape pieces
* If tape tears when removing print, replace with new piece

### Cleaning
To clean the 2 Bar Grip for reuse between experiments, scrub all surfaces vigorously using a sponge and dish soap.

## Software

All parts sliced (aka rendered) using PrusaSlicer 2.9.2

Orient object so that the 5.5mm hooks are faceing the print bed, like so:
<p>
    <img src=Images/SlicerOrientation.jpg height="290">
   </p>

Full print settings found [here](PrinterSettings/0.6_nozzle_settings_raft_x3_7mm_spacing.ini).

### Key Settings
* No skirt, no brim
* Raft layers -> 3
* Support pattern: Rectilinear
* Support pattern spacing: 7mm
* First layer speed: 10mm/s 
* First layer height: 0.2mm 
* Infill density: 5%
* Layer Height: 0.4mm

<!--Print Settings:
Prusa i3 MK3S Printer
Prusa SLicer 2.9.2
Overture PLA Professional Filament
0.6mm Nozzle
Print Settings: (Only listed if different from default)
	Infill:
		Fill Density - 5%
	Skirt + Brim:
		Loops - 0
		Brim Type - No brim
	Support Material:
		Generate Support Material - Yes
		Raft Layers - 3
		Top Contact Z Dist - 0.3mm
		Pattern - Rectilinear
		Pattern Spacing - 7mm
		Bottom Interface Layers - Same as top
		Interface Pattern - Concentric
		Interface Pattern Spacing - 0.5mm
		XY Seperation - 90%
		Preferred Branch Angle - 25
		Branch Diameter Angle - 5°
		Branch Diameter with Double Walls - 3mm
		Tip Diameter - 0.8mm
		Branch Density - 15%
	Speed: 
		Perimeters - 35mm/s
		Small Perimeters - 20mm/s
		External Perimeters - 30mm/s
		Infill - 45mm/s
		Solid Infill - 45mm/s
		Top Solid Infill - 35mm/s
		Gap Fill - 35mm/s
		Enable Dynamic Overhang Speeds - No
		First Layer Speed - 10mm/s
	Advanced:
		Top Solid Infill - 0.65mm
		Support Material - 0.61mm -->

# Acknowledgments

* Original design by [Aaron Crane](https://github.com/atcrane9)
* Commissioned by Alika Sulaman and [The AER Lab](https://github.com/AER-Lab)­­
