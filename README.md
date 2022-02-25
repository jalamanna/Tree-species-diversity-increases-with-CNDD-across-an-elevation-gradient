# Tree-species-diversity-increases-with-CNDD-across-an-elevation-gradient
Analysis code and data for LaManna et al. "Tree species diversity increases with conspecific negative density dependence across an elevation gradient" in Ecology Letters.

The R code and data files (.RData) included in the ZIP file here run analyses from LaManna et al. "Tree species diversity increases with conspecific negative density dependence across an elevation gradient." The data are publicly available at https://andrewsforest.oregonstate.edu/data, but must be individually requested. We include R code titled "Data_Preparation" which contains, for reference, the code to merge and check data from the HJ Andrews repository that was accessed in Dec 2017. We could not include the original data CSVs obtained from that repository here because they must be individually requested and contain additional data from plots outside the HJ Andrews (throughout the Pacific Northwest) that were not used in this analysis. However, all data used in our analyses are included in the ZIP file here.

We respectfully request that you cite our paper (LaManna et al. 2022 Ecology Letters) when using this analysis code. If you desire to use the data in publication, please contact us for permission. In addition to citing the LaManna et al. paper above, please also use the following citation if using the data provided here: 

Franklin, J., Bell, D.M. & Shaw, D.C. (2021). Long-term growth, mortality and regeneration of trees in permanent vegetation plots in the Pacific Northwest, 1910 to present, ver. 16. Environmental Data Initiative.

Instructions for use of code:
1. For all analyses, make sure all files included in the zip file are in your R working directory.
2. For species richness analyses, open "HJA_LaManna_RefStand_Species_Richness_Data.RData" and run the R code: "HJA_LaManna_RefStand_Species_Richness_Analysis_Jan_2022.R".
3. For survival analyses, begin by opening "HJA_LaManna_RefStand_Survival-Growth_Data_Prep.RData" and run one of the "HJA_LaManna_RefStand_ExpSurvival_Analyses_Jan_2022...R" files.
4. For growth analyses, begin by opening "HJA_LaManna_RefStand_Survival-Growth_Data_Prep.RData" and run one of the "HJA_LaManna_RefStand_Growth_Analyses_Jan_2022...R" files.
