# Exploring patterns of environmental justice in Los Angeles County

## Description
This repository is from an assignment completed in EDS 223 (Geospatial Analysis & Remote Sensing) at the Bren School of Environmental Science & Management. Through a series of geospatial analyses, it aimed to analyze how present-day environmental justice issues reflect legacies of historical injustice due to what is colloquially known as "redlining" in Los Angeles County. This practice has had widely-documented consequences not only for community wealth, but also health. Furthermore, recent literature highlights that redlining has not only affected the environments communities are exposed to, but has also shaped our observations of biodiversity with redlined neighborhoods remaining more undersampled compared to non-redlined areas.

## Repository organization description
```
├── HW2_files
|   └── figure-HTML
|       └── fig-birds-1.png          # figure of % bird observations by HOLC grade
|       └── fig-variables-1.png      # figure of EJ screen variables by HOLC grade
|   └── libs                         # other generated files from rendering the .qmd file
├── HW2.html                         # FINAL REPORT, polished Quarto doc of the entire analysis
├── HW2.qmd                          # Quarto markdown doc used to generate the final report
├── README.md                        # description of repo
```

## Data access
All relevant data available [here](https://drive.google.com/file/d/14CauXFZkVh_6z2Euq0m1Sq1kHQ31fiMk/view?usp=drive_link). Sourced from a shared course Google Drive, and imported into RStudio using the `here`, `sf`, and `terra` packages. 

## Acknowledgements 
This assignment was created and organized Ruth Oliver, an Assistant Professor at the Bren School and the instructor for EDS 223. EDS 223 (Geospatial Analysis & Remote Sensing) is offered in the Masters of Environmental Data Science (MEDS) program at the Bren School. 

## References 
City of Los Angeles GeoHub. (2020). County Boundary. <https://geohub.lacity.org/datasets/county-boundary>

Ellis-Soto, D., Chapman, M., & Locke, D. H. (2023). Historical redlining is associated with increasing geographical disparities in bird biodiversity sampling in the United States. Nature Human Behaviour, 1-9

GBIF. (2022). Global Biodiversity Information Facility. <https://www.gbif.org/>

Nelson, K. R., Winling, L., Marciano, R., Connolly, N., “Mapping Inequality,” American Panorama, ed. Robert K. Nelson and Edward L. Ayers, accessed October 17, 2023, <https://dsl.richmond.edu/panorama/redlining/>

United States Environmental Protection Agency. 2024 version. EJScreen. <https://www.epa.gov/ejscreen>
