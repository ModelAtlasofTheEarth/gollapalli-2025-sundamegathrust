### -> submitter ORCID (or name)

0000-0001-9394-4104

### -> slug

gollapalli-2025-sundamegathrust

### -> license

CC-BY-4.0

### -> alternative license URL

_No response_

### -> model category

_No response_

### -> model status

completed

### -> associated publication DOI

https://doi.org/10.1038/s41467-025-65824-7

### -> model creators

0000-0001-9394-4104
0000-0003-2131-8723

### -> title

_No response_

### -> description

Subduction zone forces strongly influence tectonic stresses and earthquake behaviour along convergent margins. In the Sunda region (Java–Sumatra–Andaman), variations in slab pull and mantle flow control how plates move and interact. Using high-resolution 3-D models that match present-day observations, we show that the pull of the Java slab dominates regional dynamics, driving northward-increasing oblique convergence, trench advance near Sumatra, and stronger plate coupling. The modelled stress patterns agree with geodetic data and earthquake stress orientations. Frictional strength variations along the megathrust identify key depth zones that align with major earthquake locations, highlighting how deep subduction processes set conditions for seismic events.

### -> abstract

The link between great earthquakes and subduction dynamics across a wide range of scales remains a crucial, yet elusive, tenet of the seismotectonics of convergent margins. Here, we show high-performance computational simulations of the three-dimensional Sunda subduction zone dynamics matching plate motions, tectonics and current deformation, thereby providing insights into the stress regime of the Java-Sumatra-Andaman margin. Testing various tectonic forces reveals the primary control of the Java slab pull and induced mantle flow on the whole margin tectonics, driving northward-increasing oblique convergence, Sumatran trench advance and increased tectonic coupling along this segment. The modelled deviatoric stresses reproduce the geodetically-constrained interseismic compression in Sumatra and megathrust stress orientations notably consistent with the seismic P-axes, with magnitude comparable to static stresses on seismogenic faults. We map the frictional strength along the Sumatra-Andaman megathrust, identifying critical thresholds at key seismogenic depths, which remarkably correlate with the location of great earthquakes. Our outcomes show how subduction dynamics may critically prime the conditions for seismicity along the Sunda margin.

### -> scientific keywords

Subduction, stresses, sunda, earthquake

### -> funder

_No response_

### -> model embargo?

_No response_

### -> include model code ?

- [ ] yes

### -> model code/inputs DOI

_No response_

### -> model code/inputs notes

_No response_

### -> include model output data?

- [x] yes

### -> data creators

0000-0001-9394-4104

### -> model output data DOI

_No response_

### -> model output data notes

_No response_

### -> model output data size

_No response_

### -> software framework DOI/URI

https://doi.org/10.5281/zenodo.3384283

### -> software framework source repository

https://github.com/underworldcode/underworld2/tree/v2.8.1b

### -> name of primary software framework (e.g. Underworld, ASPECT, Badlands, OpenFOAM)

Underworld2

### -> software framework authors

_No response_

### -> software & algorithm keywords

_No response_

### -> computer URI/DOI

_No response_

### -> add landing page image and caption

![Image](https://github.com/user-attachments/assets/aa0337ee-7643-4388-8a23-d9bdc36bbf18)

a) Mantle flow at 300 km depth in Model 1. Arrows for horizontal flow velocities, in color for the vertical velocity. b) Mantle flow streamlines, in color for the vertical velocity. Positive vertical velocities represent mantle upwelling, whereas negative vertical velocities indicate mantle downwelling. In dark green the subducting lithosphere and blue for the subducting slab. Lower mantle in light green. a) was created with open-source software Python and library Matplotlib, b) with open-source software Paraview.

### -> add an animation (if relevant)

_No response_

### -> add a graphic abstract figure (if relevant)

<img width="3480" height="2850" alt="Image" src="https://github.com/user-attachments/assets/fec3e13a-7886-485c-bea7-3acd77df5d86" />

a) Tectonic setting of the Southeast Asian subduction zone. Black arrows indicate the relative velocity of the Indo-Australian Plate (IAP) compared to the Sunda Plate in the No-Net-Rotation (NNR) reference frame. Red arrows for trench velocities in the NNR frame. The line with squares marks the Sunda trench location. Slab depth variations in the upper mantle is shown next to the trench. Within the IAP, crustal ages are displayed in the oceanic region along with topography variations in the continental area. The solid dark red line represents the boundary of the entire IAP. The dashed dark red line indicates the internal boundary separating the Indian, Capricorn, and Australian plates within the IAP. b) Dilatation along the Sunda trench. Positive and negative values represent extension and contraction, respectively. The Sunda trench is divided into Andaman, Sumatra, and Java segments along the margin. Volcanic islands in red triangles. Contours show rupture patches of 2004, 2005, and 2007 earthquakes. c) Outline of the different models developed in this study. d) Numerical solution for the velocities of the subducting plate (magenta) and mantle flow (orange). e) Model 3a setup. In blue the subducting lithosphere, in red the interface (megathrust) to a depth of 90 km. Lower mantle tomography as in the text, converted in density contrast.

### -> add a model setup figure (if relevant)

![Image](https://github.com/user-attachments/assets/497dadac-a9ab-456c-a6ec-9caff6767f08)

Setup of Model 1, 2 and 3. The models consist of a subducting plate with an attached slab, upper plate, upper mantle, and lower mantle. The mantle depth is 1000 km in (A) and (B), and 2891 km in (C). The thickness of the upper plate is 90 km in all models. The line with open squares indicates the trace of the interface.

### -> add a description of your model setup

We model subduction in a regional spherical domain using Stokes flow of an incompressible fluid with an infinite Prandtl number. The Southeast Asian subduction zone is simulated within a portion of a spherical shell. The domain is discretised with a uniform mesh in longitude and latitude, and a non-uniform mesh in the radial direction, resulting in element sizes of ~15×15×10 km in the upper mantle and ~15×15×37 km in the lower mantle. Each element contains 20 Lagrangian particles to track material properties and improve resolution of stress variations. All model boundaries are assigned free-slip conditions.

### Please provide any feedback on the model submission process?

_No response_