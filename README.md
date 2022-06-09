# Bibliometric Analyses - SAR-based crop classifications

This repo contains two main scripts for conducting bibliometric analyses on the literature body of SAR-based crop classifications aiming at two main outcomes:
1. visualising temporal & spatial (study site) characteristics
2. identifying landmark contributions 

The general workflow used to get there is depicted below and starts from harvesting & merging metadata from Scopus and Web of Science as two main electronic databases. Most parts of the subsequent workflow are then realisied using the R Markdown script, for the identification of study sites the Jupyter Notebook comes into play. Even though the literature body of interest presented here is on SAR-based crop classifications, the general workflow is transferable to other research corpuses.

![image](figures/workflow_methods.png)

Some of the resulting visualisations generated are shown below.

![image](figures/temporal_patterns.png)
![image](figures/study_areas_map.png)
![image](figures/citations.png)