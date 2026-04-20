# Project-3-Cavalier-Kaggles

## Repository Overview

This repository contains all code, data processing steps, exploratory analysis, and results for our project. The project examines whether a transfer learning-based convolutional neural network can classify the presence or absence of thoracic disease in frontal chest x-ray images. The goal of the project is to build upon a pre-trained CNN to accurately classify diseased states. Our analysis focuses on frontal chest x-ray images from the National Institutes of Health.


## Software and Platform

### Software
We performed all data cleaning, preprocessing, exploratory analysis, and modeling in a Jupyter Notebook using a CUDA and Python 3. CUDA was used to speed up computation through GPU-enabled function and is not required for the analysis.

### Required Packages
The following Python packages are required to run the notebook:
-os
-numpy
-pandas
-matplotlib.pyplot
-PIL
-collections
-torch
-torch.nn
-torch.optim
-torch.utils.data
-torchvision
-sklearn.model_selection
-sklearn.metrics

All packages can be install via `pip` if they are not already available. 

### Platform
-Developed and tested in a local Jupyter Notebook environment using CUDA resources
-Expected to run on Windows, macOS, and Linux without modification


## Map of the Repository
Below is an outline of the repository structure and its contents:

<pre><code>project-root/
├─ DATA/
│  ├─ M3_Data_Appendix_-_Project_3.pdf
│  ├─ Data_Entry_2017_v2020.csv
│  └─ DatasetDirections.csv
├─ OUTPUT/
│  ├─ binary_label_frequencies.png
│  ├─ confusion_matrix_output.png
│  └─ original_label_frequencies.png
├─ SCRIPTS/
│  └─ DS_4002_Project_3.ipynb
├─ Cavalier_Kaggles_-_Project_3.pdf
├─ LICENSE.txt
└─ README.md
</code></pre>

## Instructions for Reproducing Results
To faithfully reproduce the results of our project, please run each cell in the DS 4002 Project 3 Jupyter Notebook (`DS 4002 Project 3 Code.ipynb`) in the order indicated within the file.

## License

This repository uses the MIT License. See `LICENSE.txt` for full details.
