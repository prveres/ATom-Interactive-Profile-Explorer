# ATom Cl2 Interactive Profile Explorer

**Interactive visualization of vertical Cl2 profiles from the NASA ATom mission**

**[View the Interactive Map](https://prveres.github.io/ATom-Interactive-Profile-Explorer/interactive_profile_map.html)**

## Overview

This interactive tool displays vertical profiles of molecular chlorine (Cl2) and related trace gases measured during the NASA Atmospheric Tomography (ATom) mission. Each marker on the map represents a vertical profile pair (ascent + descent), color-coded by Cl2 classification:

- **Green**: Cl2 > 2 pptv 
- **Red**: Cl2 <= 2 pptv 
  - **Gray**: -- background/below detection limit 0.6 ppt (3 sigma) 
   
    - Clicking a marker shows the full vertical profile with Cl2, H2O, RH, potential temperature, and other trace gases.
   
    - ## Scientific Context
   
    - Elevated daytime Cl2 (2-8 pptv) was observed in the remote marine free troposphere (2-7 km altitude) during ATom-3 and ATom-4. We propose a unified evaporative degassing mechanism: marine aerosol carrying pre-loaded halide reservoirs from MBL cycling is lofted into dry free-tropospheric air, triggering water loss, auto-acidification, and Cl2/BrCl release.
   
    - This work is described in: **Veres, P. R., D. Jeong, J. A. Neuman, et al.** (in preparation), *Evaporative degassing of marine aerosol as a source of Cl2 in the remote free troposphere*
   
    - ## Data Sources and Citations
   
    - ### ATom Mission Data
   
    - **ATom Merge Files (v2)**: Wofsy, S. C., et al. (2021). ATom: Merged Atmospheric Chemistry, Trace Gases, and Aerosols, Version 2. ORNL DAAC, Oak Ridge, Tennessee, USA. https://doi.org/10.3334/ORNLDAAC/1925
     
    - **ATom Mission Overview**: Thompson, C. R., et al. (2022). The NASA Atmospheric Tomography (ATom) Mission: Imaging the Chemistry of the Global Atmosphere. *Bull. Amer. Meteor. Soc.*, 103(3), E761-E790. https://doi.org/10.1175/BAMS-D-20-0315.1
       
    - ### Instrument Data
       
    - **Cl2 and BrCl (NOAA I-CIMS)**: Robinson, M. A., et al. (2022). An iodide-adduct chemical ionization mass spectrometer for the detection of atmospheric trace gases. *Atmos. Meas. Tech.*, 15, 4295-4313. https://doi.org/10.5194/amt-15-4295-2022
         
    - **H2O / RH (DLH)**: Diskin, G. S., et al. (2002). Open-path airborne tunable diode laser hygrometer. *Diode Lasers and Applications in Atmospheric Sensing*, SPIE Proc., 4817, 196-204.
           
    - **Aerosol Composition (AMS)**: Schill, G. P., et al. (2020). Widespread biomass burning smoke throughout the remote troposphere. *Nat. Geosci.*, 13, 422-427. https://doi.org/10.1038/s41561-020-0586-1
             
    - **Single-Particle Composition (PALMS)**: Froyd, K. D., et al. (2019). A new method to quantify mineral dust and other aerosol species from aircraft platforms using single-particle mass spectrometry. *Atmos. Meas. Tech.*, 12, 6209-6239. https://doi.org/10.5194/amt-12-6209-2019
               
    - **Meteorological Data (MMS)**: Scott, S. G., et al. (1990). The Meteorological Measurement System on the NASA ER-2 Aircraft. *J. Atmos. Oceanic Technol.*, 7, 525-540.
                 
    - ### Reanalysis Data
                 
    - **MERRA-2**: Gelaro, R., et al. (2017). The Modern-Era Retrospective Analysis for Research and Applications, Version 2 (MERRA-2). *J. Climate*, 30, 5419-5454. https://doi.org/10.1175/JCLI-D-16-0758.1
                   
- ## ATom Campaign Details
                   
- | Campaign | Dates | Season |
- |----------|-------|--------|
- | ATom-3 | Sep 28 - Oct 27, 2017 | NH Autumn |
- | ATom-4 | Apr 24 - May 21, 2018 | NH Spring |
                   
- Flight routes: pole-to-pole transects over the Pacific and Atlantic oceans on the NASA DC-8 aircraft.
                   
- ## Contact
                   
- Patrick R. Veres -- NSF NCAR Research Aviation Facility --
- https://www.airborne-science.com
- pveres@ucar.edu
