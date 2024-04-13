READ ME FILE
----------------------------------------------------------

REQUIRED PACKAGES
 - tidyverse
 - dplyr
 - lme4
 - lmerTest
 - ggpubr
 - vegan
 - gtools
 - car


DATASETS
 - EEB397_InvertData.csv
    - pondID: Pond and depth identifier.
    - depth: Depth of colony plates. 
    - SampleSize: Number of specimens 
    - n<Taxonomic Family>: Number of specimens found within the taxonomic family. 
 - Urban_Stream_2023_Site_Sample_Data_VP.csv
    - Pond: Pond where the vertical profiles were taken.
    - SampleID: Pond and depth identifier.
    - Date: Date where the vertical profiles were conducted.
    - Time In: Time when vertical profiles observations were taken.
    - Depth: Depth of the observation. 
    - Temperature: Temperature observed at given depth. 
    - DO: Dissolved oxygen observed at given depth.
    - Conductivity: Conductivity observed at given depth.
    - Turbidity: Turbidity observed at given depth. 
    - Num: Indicator of month where vertical profile was conducted (1 for July and 2 for August).


PLOTS
Generated plots are stored in the Plots folder. Visualizations were done using ggplot2 and vegan. 
