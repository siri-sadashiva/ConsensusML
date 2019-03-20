# ConsensusML - Model Accuracy in Identifying Key Genes in AML 


# Background
Leukemia is a cancer of the blood arising in white blood cells of the bone marrow. It poses a substantial population burden as the most common pediatric cancer (Steliarova-Foucher et al 2017; SEER data). Acute Myelogenous Leukemeia (AML) is a type of leukemia impacting the myeloblast stem cells. AML arises at a current rate of approximately 20,000 cases per year, with 27.4% 5-year survival 2. It is a molecularly heterogeneous cancer, with several clinically relevant subtypes, including perhaps dozens of subtypes defined by factors ranging from cell differentiation state to cytogenic and sequencing assays (Yi G. et al 2019; Tyner J. W. et al 2018). Pediatric AML is characterized at a molecular level by rare somatic mutations, absence of common adult AML mutations, and relatively frequent structural variants (Bolouri H et al 2018). Here, we apply several machine learning approaches for feature selection of RNA-seq data from both pediatric and adult AML cases. Our goal was to better understand gene expression-based heterogeneity underlying AML cases, as well as age-related and -unrelated dysregulation patterns. We used clinical and assay data from pediatric cancer patients from the Therapeutically Applicable Research To Generate Effective Treatments (TARGET) initiative (https://ocg.cancer.gov/programs/target/).

### Project
This project builds on the ConsensusML project ( https://github.com/NCBI-Hackathons/ConsensusML ) by selecting features through Pearson's correlation coefficient and implementing a Random Forest classification method.The classification consists of two groups of patients, high risk and low risk.

### Dependencies
The notebook(BioInformatics_AML.ipynb) contains the required dependencies to be installed in the cell itself. However, if in case the installation fails after running the cell, please install the follwing by running the commands in terminal

### Scikit:
conda install scikit-learn (OR)
pip install -U scikit-learn

### Matplotlib:
conda install -c conda-forge matplotlib (OR)


pip install --upgrade setuptools
pip install matplotlib


### Pandas:
conda install pandas (OR)
pip install pandas

### Numpy 
conda install -c anaconda numpy (OR)
pip install numpy

### Other requirements:
1. When running the BioInformatics_AML.ipynb notebook, please make all the folders Clinical_Data, Expn_Data, Manifest_Data and clean.py file are present in the same directory.
2. While reading the csv files, change the pathname to read the files from the current directory. 
