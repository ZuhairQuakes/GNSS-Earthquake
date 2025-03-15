# Automated Earthquake Risk Assessment using Global Navigation Satellite System (GNSS) data

This repository contains a comprehensive Python implementation for computing strain rates (*an indicator for stress accumulation within the Earth leading to earthquakes*) using GPS velocity field data. Designed to enhance geospatial data processing, the project automates strain computation and visualization, providing key insights into tectonic activity and earthquake-prone regions. The solution is highly modular, scalable, and tailored for professionals in space geodesy, geophysics, and data science.

## Key Features:

- Automates preprocessing, gridding, and computation workflows to handle multi-resolution large datasets.
- Parallelized workflows reduce computation time for scalable analysis.
- Handles diverse geospatial inputs with automated filtering and transformations.
- Enables integration with tools like Cartopy or GIS platforms.
- Capable of processing datasets spanning hundreds of kilometres with high-resolution grids.
- Generates actionable insights into tectonic activity for disaster risk management and infrastructure planning.

---------------
## Examples

**Singapore**
![**Strain Rates**](images/singapore_result.png "Strain Rates")
The map illustrates the distribution of maximum shear strain across the region, highlighting high-strain zones (earthquake-prone regions) and low-strain stable zones, GPS station locations (black dots), deformation directions represented by arrows, and the presence of fault lines (black curves), which correlate with the strain distribution. The purpose of the study is to analyze surface deformation patterns and identify zones of tectonic stress accumulation. This analysis has applications in urban planning and infrastructure resilience, providing critical insights for mitigating risks in geologically active regions.

---------

**Myanmar**
![**Strain Rates**](images/result_mynamar.png "Strain Rates")
This visualization represents the second invariant of the strain tensor, calculated over three different spatial grids of resolutions: 0.1° x 0.1°, 0.2° x 0.2°, and 0.3° x 0.3°. It depicts geospatial variations in strain rates over a region and is used to study tectonic deformation and seismic hazards in Myanmar.

----------

## How to Use:
1. Input GPS velocity field data in a compatible format.
2. Configure grid sizes and computation parameters.
3. Run the gpsgridder module to compute strain tensor components.
4. Visualize results using any GIS-compatible platform or integrate them into ML workflows.








   
