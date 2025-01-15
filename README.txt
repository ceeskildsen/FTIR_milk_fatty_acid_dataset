# Dataset Repository

This repository contains data from a study involving the fatty acid composition of milk from individual cows. The dataset comprises 890 a.m. milk samples (435 Jersey and 455 Holsteins), which were collected as part of the Danish-Swedish Milk Genomics Initiative ([www.milkgenomics.dk](http://www.milkgenomics.dk)).

## Dataset Description

### Overview
A total of 890 milk samples were included in this study, originating from two distinct breeds:
- 435 Jersey cows
- 455 Holstein cows

The sampling strategy was designed to minimize environmental variation while maximizing the genetic variation of the sample population. The Holstein samples were collected from 20 Danish dairy herds between October and December 2009, while the Jersey samples were collected from 22 Danish dairy herds between February and April 2010. All samples were obtained from conventional herds and collected while cows were housed (Poulsen et al., 2012).

### Data Format
The dataset is provided in MATLAB format and is structured for use with the PLS_Toolbox from Eigenvector Research. Users will need a valid PLS_Toolbox license to read and analyze the data.

### Data Collection and Analysis
- **Quantification of Fatty Acids (FA):**
  - Fatty acid levels were quantified using gas chromatography (GC) as described by Poulsen et al. (2012).

- **Fourier Transform Infrared (FT-IR) Spectroscopy:**
  - Full FT-IR spectra were recorded for all samples using the MilkoScan FT2 (Foss Analytical A/S, Hillerød, Denmark).
  - Spectra were obtained from fresh whole milk, with measurements conducted in triplicate.
  - For each FT-IR measurement, a water spectrum was subtracted, and the average difference spectrum of each sample (across three replicates) was used for further analysis.

### Additional Features
The dataset includes predictions of fatty acids based on FT-IR measurements. These predictions account for interactions between total fat content (TF) and breed (TF × Breed), along with variation independent of these interactions. 

For a detailed explanation of the data and preprocessing, please see Poulsen et al. (2012) and Eskildsen et al. (2014).

## Terms of Use

By accessing or using this dataset, you agree to the following terms:

1. **Non-Commercial Use**:
   - This dataset is made available for non-commercial use only. It may not be used for commercial purposes without explicit permission.

2. **Citation Requirement**:
   - If you use this dataset in your research, publications, or any other derivative works, you must cite the following references:

     - Poulsen, N. A., F. Gustavsson, M. Glantz, M. Paulsson, L. B. Larsen, and M. K. Larsen. 2012. "The influence of feed and herd on fatty acid composition in 3 dairy breeds (Danish Holstein, Danish Jersey, and Swedish Red)." *Journal of Dairy Science*, 95:6362–6371.
     
     - Eskildsen, C. E., M. A. Rasmussen, S. B. Engelsen, L. B. Larsen, N. A. Poulsen, and T. Skov. 2014. "Quantification of individual fatty acids in bovine milk by infrared spectroscopy and chemometrics: Understanding predictions of highly collinear reference variables." *Journal of Dairy Science*, 97:7940-7951. [https://doi.org/10.3168/jds.2014-8337](https://doi.org/10.3168/jds.2014-8337)

## License

This dataset is distributed under the [Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).

## Contact

For any questions or requests regarding this dataset, please contact Carl Emil Eskildsen, carl.emil.eskildsen [at] gmail [dot] com.
