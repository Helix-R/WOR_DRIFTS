Author: Helix Robles
Contact: Helix.Roblez@gmail.com
Date: 8/5/2026

This folder contains 4 R markdown files and 6 R data files for the manuscript (Robles et al., 2026):
Characterization of Particulate and Mineral-Associated Organic Matter in Wood Chip Amended Sandy Loam Soil: Composition and Distribution Across Space-Time

[RMD]						[RDS]
Raw_spectra.rmd				SFT_POM_MAOM_raw.rds
Subtracted_Spectra.rmd		SFT_POM_MAOM_sub_KM.rds
Averaged_Spectra.rmd		SFT_POM_MAOM_sub_KM_ave.rds
SFT_Chem_stats.rmd			SFT_2023_Metadata.rds
							Helix_Index123.rds
							POM_MAOM_TC_TN_Subtraction.rds

Briefly, the acronyms used in the file names are:
(SFT) Space for Time Substitution experimental design
(WOR) Whole Orchard Recycling
(POM) Particulate Organic Matter
(MAOM) Mineral Associated Organic Matter
(sub) Spectral subtraction 
(KM) Kubelka-Munk Transformed
(KB) Kearney Block
(TC) Total Carbon
(TN) Total Nitrogen 

The purposes of each file/analysis are as follows:

Raw_spectra.rmd:
This file is for analysis of the raw spectral files, which contains all replicates (4 replicate blocks were sampled for each Treatment x Field combination).
Here we have the raw POM and MAOM spectra (labeled individually as POM and MAM), with corresponding bleached (NaOCl oxidized) POM and MAOM samples (labeled as PX and MX).
Note: All samples were air-dried, diluted to 10% (w/w) with pre-ground potassium bromide (KBr).
Spectra Data File: SFT_POM_MAOM_raw.rds

Subtracted_Spectra.rmd:
This files is for analysis of the spectral subtaction data, for each replicate, where the soil mineral contribution was subtracted out.
Here the bleached POM samples were subtracted from the untreaded POM samples (POM - PX = POM subtraction spectra).
Similarly, the bleached MAOM samples were subtracted from the untreated MAOM samples (MAM - MX - MAOM subtraction spectra).
Note: The spectral subtractions were performed manually in OMNIC for each sample, targeting the removal of Si-O bond absorbances. KM-transformation was also performed in OMNIC.
Spectra Data File: SFT_POM_MAOM_sub_KM.rds

Averaged_Spectra.rmd:
This file is for analysis of the averaged spectral subtraction data for both POM and MAOM samples.
Here the replicate subtraction spectra were averaged in OMNIC, resulting in 1 spectra for each Treatment x Field combination.
Note: The spectra were averaged and then KM transformed.
Spectra Data File: SFT_POM_MAOM_sub_KM_ave.rds

SFT_Chem.rmd:
This file is for analysis of the soil chemistry data for all values, including Index values.
Here we have all the metadata for the <2 mm soil and corresponding POM and MAOM fractions. The POM and MAOM samples have TC, TN, and C:N ratio data.
The <2 mm soil fractions have TC, TN, C:N, SOM, WHC, pH, EOC, ExtN, MBC, MBN, and CO2 respiration data (incubated with both as 16O and 18O water).
Note 1: This file also contains code for the bleach treated POM and MAOM supplemental figure (as proof that the PX and MX samples were thoroughly bleached, down to near 0% total carbon).
Note 2: The individual plots of soil chemistry variables were combined and annotated with Affinity (photo editing software).
Soil (<2 mm), POM, and MAOM Chemistry Data: SFT_2023_Metadata.rds
Helix Index Values Data: Helix_Index123.rds

SFT_stats.rmd:
This file is for statistics of all soil chemistry data and index values (<2 mm soil and corresponding POM and MAOM fractions).
The <2 mm soil fractions have TC, TN, C:N, SOM, WHC, pH, EOC, ExtN, MBC, MBN, and CO2 respiration data (incubated with both as 16O and 18O water).
Note: The soil chemistry plots were annotated with significant post-hocs using Affinity (photo editing software).
Soil (<2 mm), POM, and MAOM Chemistry Data: SFT_2023_Metadata.rds
Helix Index Values Data: Helix_Index123.rds
