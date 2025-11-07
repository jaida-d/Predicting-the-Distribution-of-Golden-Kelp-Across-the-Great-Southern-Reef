# Predicting-the-Distribution-of-Golden-Kelp-Across-the-Great-Southern-Reef
Predicting the Distribution of Golden Kelp Across the Great Southern Reef Under Future Climate Scenarios

**Datasets:**
Data used for this report can be accessed by the following links:
- imos data: https://catalogue-imos.aodn.org.au/geonetwork/srv/eng/catalog.search#/metadata/ec424e4f-0f55-41a5-a3f2-726bc4541947 
- gbif data: https://doi.org/10.15468/dl.az6pza 
- Bio-ORACLE: https://www.bio-oracle.org/downloads-to-email.php 

**Summary:**
Our aims with this research are to determine which environmental variables are most important for predicting the distribution of *Ecklonia Radiata* across the Great Southern Reef, and to predict the future distribution of *Ecklonia Radiata* for the periods 2040-2050 and 2090-2100, under three climate scenarios (SSP1, SSP2 and SSP3). Using environmental data from Bio-ORACLE, we will evaluate which variables are the most influential, and use these to create predictions from three models: a Generalised Linear Model, Maxent and Random Forest. We will then evaluate and compare their predicted outputs for suitable habitat and species distributions, to determine the potential impacts of climate change on *Ecklonia Radiata*.

**Scientific Hypotheses:**
We hypothesise that range contraction for *Ecklonia Radiata* will occur under all SSP scenarios in 2040-2050, but will be greatest under SSP3 and smallest under SSP1. For SSP2 and SSP3, we expect that greater range contraction will occur at 2090-2100 compared to 2040-2050. Under SSP1, however, the range of suitable habitat is predicted to expand back towards present-day levels in 2090-2100 - following the improvement in environmental conditions at this time point. All environmental variables discussed are expected to contribute to the models.\

**Key Findings:**
The GLM and MaxEnt model predicted that under the best-case scenario (SSP1), by 2040-2050, the range of suitable habitat will have contracted by over 96%. Although habitat suitability largely recovers by 2090-2100 under SSP1, it is unlikely that Ecklonia radiata will be able to repopulate the GSR without intervention. Under the middle-of-the road (SSP2) and worst case (SSP3) climate scenarios, 96-100% of suitable habitat is predicted to be lost by 2040-2050, and 99.7-100% by 2090-2100. Our findings emphasise the need for adaptive management strategies to prevent the extinction of Ecklonia radiata across the GSR.

**Some of the Key Guides We Used:**
- A very brief introduction to species distribution models in R, by Tristan Salles 
- FW840: Landscape Ecology - Week 4: Species Distribution Modelling, by Patrick Hanly (2025): https://bookdown.org/pjhanly/fw840hanly/week-4-species-distribution-models.html
- EcoCommons Australia Generalised Linear Model (GLM) tutorial available at EcoCommons Australia GLM Notebook (EcoCommons Australia, 2023): https://ecocommonsaustralia.github.io/notebook-blog/notebooks/EC_GLM/EC_GLM.html
