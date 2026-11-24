# fly-by
a VTOL drone 
<img width="1174" height="614" alt="Figure-15" src="https://github.com/user-attachments/assets/83d932d1-65b1-441b-8ff9-4a8d8b6512bb" />

Fly-By

A collection of 3D aircraft model files and related printable parts.

This repository contains MH7 aircraft components in STL and 3MF formats, along with MH5 reduced-geometry STL models intended for simulation or lightweight 3D use.
Repository Contents
stl-SourceFiles/

STL source meshes for individual MH7 aircraft components, including:

    Wings and winglets
    Nose and empennage
    Fins
    Tilt mounts and nacelle parts
    Battery tray and motor spacer
    Hatches and FPV hatch options
    Control horn and locking latch
    Weight-balance stand beam

These files are individual mesh parts. Select the appropriate part or variant for your build.
3mf-Implementations/

3MF model sets for selected MH7 parts and assemblies:

    MH7_Hatch-FPV_Set.3mf
    MH7_WeightBalanceStand_Set.3mf
    MH7_WingLeft-Solar.3mf
    MH7_WingLeft.3mf
    MH7_Winglet_Set.3mf

3MF files can preserve model arrangement and may include slicer/project information depending on how they were exported.
sim-ReducedGeometry/

Reduced-geometry MH5 STL models, including the airframe, elevons, and tilt mounts. Multiple LOD (Level of Detail) versions are provided for selected parts:

    LOD-0 — higher-detail mesh
    LOD-2 — lower-detail mesh

Some parts also include BREP-named mesh files.
How to Use the Models
View or prepare for 3D printing

    Download or clone this repository.
    Open an STL or 3MF file in a compatible 3D viewer or slicer, such as Ultimaker Cura, PrusaSlicer, or Bambu Studio.
    Check the model orientation, scale, and fit before printing.
    For 3MF sets, inspect the included parts and arrangement before slicing.
    Export or slice using settings appropriate for your printer and material.


The repository contains mesh assets; it does not currently document a complete simulator project, aircraft electronics setup, or flight configuration.
File Formats
Format	Purpose
.stl	Individual 3D mesh parts
.3mf	Grouped 3D model / print sets

