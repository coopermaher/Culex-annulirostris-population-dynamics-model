# 🌟 Highlights

- This repository provides the required files to replicate the results and figures in the associated preprint: [Modelling *Culex annulirostris* population dynamics at a temperate semi-arid site in the Murray Valley, south-eastern Australia](https://doi.org/10.21203/rs.3.rs-9879430/v1).
- This repository implements a population dynamics model of the mosquito species *Culex annulirostris* in the Murray Valley, south-eastern Australia.


# ℹ️ Overview

## License

The source code in this repository is licensed under the MIT License.

Dataset-specific licensing and attribution information is provided below.

## Datasets
### Params_data.csv
Created by the authors by collating relevant data from published literature of *Cx. annulirostris*.
Used in `Cx_annulirostris_temp_params.ipynb` for parameter fitting.

License: CC BY 4.0.

### Kanyapella.csv
Derived from SILO climate data.
Used for model simulations in `Model_1.ipynb`, `Model_2.ipynb`, `Model_3_1.ipynb`, `Model_3_2.ipynb`, `Model_4_1.ipynb`, and `Model_4_2.ipynb` and plotting the climatic variables for `Climate_data.ipynb`.

Original data source: SILO (Queensland Government).
Subsetted to the dates and variables used in this study.
Original data licensed under CC BY 4.0.

### Kanyapella_previous_30_years.csv
Derived from SILO climate data.
Used for fitting rainfall and water balance thresholds in `Water_indices_thresholds.ipynb`.

Original data source: SILO (Queensland Government).
Subsetted to the dates and variables used in this study.
Original data licensed under CC BY 4.0.

### Russell_1986_data_extraction.csv
Digitised from Figure 1 in:

Russell, R.C. (1986). Seasonal activity and abundance of the arbovirus vector *Culex annulirostris* Skuse near Echuca, Victoria, in the Murray Valley of southeastern Australia, 1979–1985. *Australian Journal of Experimental Biology and Medical Science*, 64, 97–103. DOI: 10.1038/icb.1986.11.

Provided solely to facilitate replication of the analyses presented in this repository.
Used to compare model performance from simulations in `Model_1.ipynb`, `Model_2.ipynb`, `Model_3_1.ipynb`, `Model_3_2.ipynb`, `Model_4_1.ipynb` and `Model_4_2.ipynb` with field data.

The underlying data originate from the cited publication. Users should consult the original source for copyright and reuse conditions.

## Code:

`Climate_data.ipynb` was used for plotting the climatic variables in the sample site over the study period.

`Cx_annulirostris_temp_params.ipynb` was used for fitting *Cx. annulirostris* parameters and plotting.

`Model_1.ipynb`, `Model_2.ipynb`, `Model_3_1.ipynb`, `Model_3_2.ipynb`, `Model_4_1.ipynb`, and `Model_4_2.ipynb` were all used to run the relevant model variations. These notebooks generate model outputs, including figures and performance metrics.

`Water_indices_thresholds.ipynb` was used for fitting rainfall and water balance thresholds and generating the corresponding classification figure.

## ✍️ Authors

These files are provided by [Cooper Maher](https://github.com/coopermaher) to support reproducibility of the associated manuscript.

## Citation

If you use this code or data, please cite:

[full paper citation]

The citation is currently pending as the manuscript is under review.
