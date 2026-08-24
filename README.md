# Revisiting-Dunne-Diagram-Code

__Revisiting Dunne Diagram: Seasonal Variation and Spatial Pattern of Runoff Components__

Yuanqi Hong<sup>1</sup>, Guta Wakbulcho Abeshu<sup>2</sup>, Hong-Yi Li<sup>1,3*</sup>, Dingbao Wang<sup>4</sup>, Mengqi Zhao<sup>5</sup> , Thomas Wild<sup>6</sup>, and L. Ruby Leung<sup>2</sup><br> 
<sup>1</sup> Department of Civil and Environmental Engineering, University of Houston, Houston, 77204, USA<br>
<sup>2</sup> Atmospheric, Climate, & Earth Sciences Division, Pacific Northwest National Laboratory, Richland, 99354, USA<br>
<sup>3</sup> Now at Department of Civil and Environmental Engineering and Center for Catastrophe Modeling and Resilience, Lehigh University, Bethlehem, 18015, USA<br>
<sup>4</sup> Department of Civil, Environmental and Construction Engineering, University of Central Florida, Orlando, 32816, USA<br>
<sup>5</sup> Earth and Environmental Directorate, Pacific Northwest National Laboratory, Richland, 99354, USA<br>
<sup>6</sup> Joint Global Change Research Institute, Pacific Northwest National Laboratory, College Park, MD 20740, USA<br>


*Corresponding author: Hong-Yi Li (hol525@lehigh.edu)


## Abstract
The classic Dunne Diagram qualitatively illustrates how atmospheric conditions, soil, and topography shape runoff generation mechanisms under long-term average conditions. This study revisits the diagram using a novel theoretical framework that unifies infiltration excess and saturation excess runoff into a continuous scheme governed by dynamic soil moisture variations across catchments. The framework captures the spatial and temporal transitions between runoff mechanisms. Using observational data from 600 natural catchments across diverse U.S. atmospheric conditions and landscapes, we develop a data-driven, quantitative reinterpretation of the Dunne diagram based on multi-annual catchment behavior, and further examine runoff generation mechanisms at seasonal timescale. At the mean annual scale, saturation excess runoff dominates the West Coast and Eastern U.S., infiltration excess runoff prevails in central regions, and baseflow dominates the Western interior and Appalachian areas. In the western U.S., both saturation- and infiltration-excess runoff exhibit strong seasonality, closely following the precipitation patterns along the West Coast. Individual catchments show seasonal switching and coexistence of dominant runoff generation mechanisms. The Unified Scheme for Modeling Saturation and Infiltration Excess Runoff (URSSIE) model broadly reproduces the general pattern of the Dunne diagram and provides quantitative support for the Dunne diagram. This approach enhances the understanding of runoff processes and improves hydrologic modeling at catchment scales, with important implications for flood forecasting and water resource management in complex or changing hydrologic regimes.



## Code reference
The analysis and visualization code used in this manuscript can be found at https://github.com/yhong11/Revisiting-Dunne-Diagram-Code

## Data reference
### Input data

The following datasets are required to run the model.


- **Forcing, streamflow and catchment attribute data**:  
Daily forcing data, streamflow observations and catchment attributes for 600 natural catchments across the contiguous United States during 1985–2014 were obtained from the CAMELS dataset (Newman et al., 2015).

Data access:  
http://dx.doi.org/10.5065/D6MW2F4D


### Output data
Data access:  https://doi.org/10.5281/zenodo.22004283
## Reproduce my experiment
The URSSIE model code used to generate the simulation outputs is available at https://github.com/yhong11/URSSIE

## Reproduce my figures
Use the scripts found in this repository to reproduce the figures used in this publication.
1. Get the model output data from your simulation or download it from https://doi.org/10.5281/zenodo.22004283
2. Open the `FigX_xxx.ipynb` you want to reproduce and run all cells.


