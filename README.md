# kaggle-moa-prediction

*Data Science @ UCSC, 01/10/2020*

Our repository for work relating to the Kaggle MOA competition

## Setup

Create a conda environment with all the required packages: 
```
conda env create -f environment.yml
```
Switch to the new environment:
```
conda activate kaggle-moa-prediction
```


## Project structure
```├── environment.yml          <- The conda file for reproducing the analysis
|                               environment. 
├── LICENSE
├── README.md                <- The top-level README
├── run.py                   <- Script with option for running the final analysis.
├── data
|   ├── interim              <- Intermediate data that has been transformed.
│   ├── processed            <- The final, canonical data sets for modeling.
│   └── raw                  <- The original, immutable data dump.
├── notebooks                <- Jupyter notebooks.
├── output             
|   ├── models               <- Serialized models, predictions, model summaries.
|   └── visualization        <- Graphics created during analysis.
└── src                      <- Source code for this project.
    ├── __init__.py          <- Makes this a python module.
    ├── data                 <- Scripts to download or generate data.
    |   └── make_dataset.py  
    ├── features             <- Scripts to turn raw data into features for modeling.
    |   └── build_features.py  
    ├── models               <- Scripts used to generate models and inference results.
    └── visualization        <- Scripts to generate graphics.
        └── visualize.py
```
    
## License

This project is distributed under the  MIT license.