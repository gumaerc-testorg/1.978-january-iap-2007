---
content_type: page
learning_resource_types:
- Projects
ocw_type: CourseSection
title: Projects
uid: 90f60c06-d578-ff04-ac25-c2799d5bf7d9
---

Final Project Introduction ([PDF]({{< baseurl >}}/resources/project_intro-1))

Problem A ([PDF]({{< baseurl >}}/resources/project_a-1))

Problem B ([PDF]({{< baseurl >}}/resources/project_b-1))

Problem C ([PDF]({{< baseurl >}}/resources/project_c-1))

### For Problem C

Initial structure ([PDB]({{< baseurl >}}/resources/geometry_start)) This is the initial structure (obtained from Protein Data Bank; after processing).  
Structure file ([PSF]({{< baseurl >}}/resources/out))  
Initial fix.pdb file (specify fixed atoms) ([PBD]({{< baseurl >}}/resources/fix))  
Initial smd.pdb file (specify atoms that are being pulled) ([PDB]({{< baseurl >}}/resources/smd))

### Simulation Results

CMDF - Log file run mode I (short) ([XYZ]({{< baseurl >}}/resources/xrunmodeishort)) This .xyz file shows a sequence of crack propagation (1,000 steps, as in the example script given above). Frequency of snapshot writing, time step etc. is the same in all examples, and equal to the example script. You may directly load this file into VMD and carry out the analysis.

CMDF - Log file run mode II ([XYZ]({{< baseurl >}}/resources/all)) Log file for 2,000 step mode II (shear run).

CMDF - xyz file - mode II, shear ([XYZ]({{< baseurl >}}/resources/xrunshear)) This .xyz file shows a sequence of 2,000 steps under shear loading. Frequency of snapshot writing, time step etc. is the same in all examples, and equal to the example script.

NAMD - Initial geometry for pulling ([COOR]({{< baseurl >}}/resources/1gk6s))

NAMD - tensile deformation 0.002 rate (F-x-curve) ([JPG]({{< baseurl >}}/resources/fxcurve_002))

NAMD - tensile deformation 0.001 rate ([DCD]({{< baseurl >}}/resources/out_small_001))

NAMD - tensile deformation 0.0005 rate (F-x-curve) ([JPG]({{< baseurl >}}/resources/fxcurve_005))

NAMD - tensile deformation 0.0005 rate ([DCD]({{< baseurl >}}/resources/out_small_005))

NAMD - bending load (force-displacement plot) ([JPG]({{< baseurl >}}/resources/bending_load))

NAMD - bending load ([DCD]({{< baseurl >}}/resources/out_small_bending_load))

NAMD - tensile deformation 0.002 rate (data file for force-displacement plot) ([DAT]({{< baseurl >}}/resources/sim1)) NOTE: Order of columns: Displacement (in Angstrom), force (in pN). This applies to all .dat files.

NAMD - tensile deformation 0.001 rate (data file for force-displacement plot) ([DAT]({{< baseurl >}}/resources/sim2))

NAMD - tensile deformation 0.0005 rate (data file for force-displacement plot) ([DAT]({{< baseurl >}}/resources/sim3))

NAMD - bending deformation (data file for force-displacement plot) ([DAT]({{< baseurl >}}/resources/bending))