# *Brucella* strain zoonotic potential prediction models
This repository contains the code and data to reproduce all analyses from the "Machine learning based on pangenome-wide association studies reveals the impact of host source on the zoonotic potential of closely related bacterial pathogens" paper.  
## Requirements
  We recommend using Anaconda3 to create a conda python environment for this project. The environment configuration file **environment.yaml** is provided in the repository.  

  We recommend a computer with the following hardware properties:

RAM: ≥16 GB  
  
CPU: Support Intel&reg; Extension for Scikit-learn  

## Usage  
1.Create the conda environment: `conda env create -f environment.yaml -n ml-enviroment`  

  
2.Data Preparation:  
- Unzip **`Data.zip`**
- Verify the **`Data`** directory contains these files: 
  - Decision_value_species_host.xlsx  
  - gene_presence_absence.csv  
  - Significant_genes.csv  
  - Species host of Brucella strains.xlsx 
  - trait.csv
    
File Structure:  

├── Brucella-strain-zoonotic-potential-predict-model.ipynb  
└── Data/  
&emsp;&emsp;├── Decision_value_species_host.xlsx  
&emsp;&emsp;├── gene_presence_absence.csv  
&emsp;&emsp;├── Significant_genes.csv  
&emsp;&emsp;├── Species host of Brucella strains.xlsx  
&emsp;&emsp;└── trait.csv  

  
3.Notebook to run:   `Brucella-strain-zoonotic-potential-predict-model.ipynb`  

  
4.Execute the notebook cells sequentially.  

## Contact
If you have any comments, questions or suggestions, please contact:  

Cheng Han, E-mail: [hancheng0099@163.com](hancheng0099@163.com)
