# New [M@TE](https://mate.science/)! model: 
 _we have provided a summary of your model as a starting point for the README, feel free to edit_
## Section 1: Summary of your model   

**Model Submitter:**  

Thyagarajulu Gollapalli ([0000-0001-9394-4104](https://orcid.org/0000-0001-9394-4104))

**Model Creator(s):**  

- Thyagarajulu Gollapalli ([0000-0001-9394-4104](https://orcid.org/0000-0001-9394-4104))  
  
**Model slug:**  

`gollapalli-2025-sundamegathrust` 

(this will be the name of the model repository when created) 

**Model name:**  

_Bridging the gap between subduction dynamics and the long-term strength of the Sunda megathrust_  

**License:**  

[Creative Commons Attribution 4.0 International]( https://creativecommons.org/licenses/by/4.0/legalcode.txt)

**Model Category:**  

  
**Model Status:**  

- completed   
  
**Associated Publication title:**  

_[Bridging the gap between subduction dynamics and the long-term strength of the Sunda megathrust](https://doi.org/10.1038/s41467-025-65824-7)_ 

**Short description:**  

Subduction zone forces strongly influence tectonic stresses and earthquake behaviour along convergent margins. In the Sunda region (Java–Sumatra–Andaman), variations in slab pull and mantle flow control how plates move and interact. Using high-resolution 3-D models that match present-day observations, we show that the pull of the Java slab dominates regional dynamics, driving northward-increasing oblique convergence, trench advance near Sumatra, and stronger plate coupling. The modelled stress patterns agree with geodetic data and earthquake stress orientations. Frictional strength variations along the megathrust identify key depth zones that align with major earthquake locations, highlighting how deep subduction processes set conditions for seismic events.

**Abstract:**  

The link between great earthquakes and subduction dynamics across a wide range of scales remains a crucial, yet elusive, tenet of the seismotectonics of convergent margins. Here, we show high-performance computational simulations of the three-dimensional Sunda subduction zone dynamics matching plate motions, tectonics and current deformation, thereby providing insights into the stress regime of the Java-Sumatra-Andaman margin. Testing various tectonic forces reveals the primary control of the Java slab pull and induced mantle flow on the whole margin tectonics, driving northward-increasing oblique convergence, Sumatran trench advance and increased tectonic coupling along this segment. The modelled deviatoric stresses reproduce the geodetically-constrained interseismic compression in Sumatra and megathrust stress orientations notably consistent with the seismic P-axes, with magnitude comparable to static stresses on seismogenic faults. We map the frictional strength along the Sumatra-Andaman megathrust, identifying critical thresholds at key seismogenic depths, which remarkably correlate with the location of great earthquakes. Our outcomes show how subduction dynamics may critically prime the conditions for seismicity along the Sunda margin.

**Scientific Keywords:**  

- Subduction   
- stresses   
- sunda   
- earthquake   
  
**Funder(s):**  
- _No response_   
  
## Section 2: your model code, output data  

**No embargo on model contents requested** 

**Include model code:**   

False 

**Include model output data:**   

True 

## Section 3: software framework and compute details   
**Software Framework DOI/URL:**  

Found software: _[Underworld2](https://doi.org/10.5281/zenodo.3384283)_ 

**Software Repository:**   

https://github.com/underworldcode/underworld2/tree/v2.8.1b 

**Name of primary software framework:**  

Underworld2 

**Software framework authors:**  
- Jmansour   
- Owen Kaluza   
- Julian Giordani   
- Romain Beucher   
- Rebecca Farrington   
- Gareth Kennedy   
- Louis Moresi   
- , Mirko   
- Adambeall   
- Arijit Laik   
- Dan Sandiford   
- Ben Mather   
  
## Section 4: web material (for mate.science)   
**Landing page image:**  

Filename: [graphics/Image.jpg](https://github.com/user-attachments/assets/aa0337ee-7643-4388-8a23-d9bdc36bbf18)  
Caption:  a) Mantle flow at 300 km depth in Model 1. Arrows for horizontal flow velocities, in color for the vertical velocity. b) Mantle flow streamlines, in color for the vertical velocity. Positive vertical velocities represent mantle upwelling, whereas negative vertical velocities indicate mantle downwelling. In dark green the subducting lithosphere and blue for the subducting slab. Lower mantle in light green. a) was created with open-source software Python and library Matplotlib, b) with open-source software Paraview.  
  
**Animation:**  

Filename: [None]()  
  
**Graphic abstract:**  

Filename: [None]()  
Caption:  a) Tectonic setting of the Southeast Asian subduction zone. Black arrows indicate the relative velocity of the Indo-Australian Plate (IAP) compared to the Sunda Plate in the No-Net-Rotation (NNR) reference frame. Red arrows for trench velocities in the NNR frame. The line with squares marks the Sunda trench location. Slab depth variations in the upper mantle is shown next to the trench. Within the IAP, crustal ages are displayed in the oceanic region along with topography variations in the continental area. The solid dark red line represents the boundary of the entire IAP. The dashed dark red line indicates the internal boundary separating the Indian, Capricorn, and Australian plates within the IAP. b) Dilatation along the Sunda trench. Positive and negative values represent extension and contraction, respectively. The Sunda trench is divided into Andaman, Sumatra, and Java segments along the margin. Volcanic islands in red triangles. Contours show rupture patches of 2004, 2005, and 2007 earthquakes. c) Outline of the different models developed in this study. d) Numerical solution for the velocities of the subducting plate (magenta) and mantle flow (orange). e) Model 3a setup. In blue the subducting lithosphere, in red the interface (megathrust) to a depth of 90 km. Lower mantle tomography as in the text, converted in density contrast.  
  
**Model setup figure:**  

Filename: [graphics/Image.jpg](https://github.com/user-attachments/assets/497dadac-a9ab-456c-a6ec-9caff6767f08)  
Caption:  Setup of Model 1, 2 and 3. The models consist of a subducting plate with an attached slab, upper plate, upper mantle, and lower mantle. The mantle depth is 1000 km in (A) and (B), and 2891 km in (C). The thickness of the upper plate is 90 km in all models. The line with open squares indicates the trace of the interface.  
Description:  We model subduction in a regional spherical domain using Stokes flow of an incompressible fluid with an infinite Prandtl number. The Southeast Asian subduction zone is simulated within a portion of a spherical shell. The domain is discretised with a uniform mesh in longitude and latitude, and a non-uniform mesh in the radial direction, resulting in element sizes of ~15×15×10 km in the upper mantle and ~15×15×37 km in the lower mantle. Each element contains 20 Lagrangian particles to track material properties and improve resolution of stress variations. All model boundaries are assigned free-slip conditions.

  
