# Analysis of Spatial Transcriptomics data - I2K workshop
This repository contains the notebooks used for the 2023 I2K workshop on spatial transcriptomics data analysis.

## Data
The data used in this worksop was published along the paper [Cell segmentation in imaging-based spatial transcriptomics](https://www.nature.com/articles/s41587-021-01044-w#Abs1).  

Download the data from [here](https://drive.google.com/file/d/15E7NVjzMyqAuwL4NMGs_39PEdab0dPiX/view?usp=sharing) and unzip it inside this folder.

**Citation:**  
Moffitt, Jeffrey et al. (2021). MERFISH measurements in the mouse ileum [Dataset]. [Dryad](https://doi.org/10.5061/dryad.jm63xsjb2)

## Conda
Create a new conda environment containing the required python packages:  
`conda env create -f environment.yml`
Activate the environment to run the notebooks:  
`conda activate <env-name>`

## Notebooks
The repository contains two notebooks:  
`baysor_output.ipynb` provides code to read and inspec the raw data.  
`merfish_analysis.ipynb` provides code fro a simple analysis pippeline.