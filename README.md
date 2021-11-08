# Normative modelling demo with PCNtoolkit

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5592153.svg)](https://doi.org/10.5281/zenodo.5592153)

This repository contains tutorials on normative modeling using the [PCNtoolkit](). 

If you use these tutorials, please cite the following 

<div>
<img src="data/NormModelSetup.png" width="500"/>
</div>


`tutorials/` --> Contains the Python notebooks for all tutorials. Each tutorial is in a sub-directory within this folder. 

* 2020 Computational Psychiatry Course tutorial using Gaussian Process Regression (GPR)
* 2021 Computational Psychiatry Course tutorial using Bayesian Linear Regression (BLR)
* The Normative Modeling Framework for Computational Psychiatry. Rutherford et al. 2021. Under review at Nature Protocols. Preprint available via [BioRxiv](https://www.biorxiv.org/content/10.1101/2021.08.08.455583v1). 
* HBR_FCON. A tutorial on Hierarchical Bayesian Linear Regression using FCON data (many sites).
* For a tutorial on GAMLSS see this [repository](https://github.com/dinga92/gamlss_normative_paper) and [preprint](https://www.biorxiv.org/content/10.1101/2021.06.14.448106v1.abstract). 

`data/` --> Contains the data used in the tutorials. Data created during the cortical thickness ROI tutorial will be output into this folder. 



It is recommended to run the tutorial via Google Colab python notebooks. These are essentially Jupyter notebooks run in the *cloud*. Running the code using Colab will save us from dealing with python library installation and virtual environment setup. You can also locally clone this repository to your computer, however you are responsible for setting up your own python environment and installing the dependencies. Read more on how to do this and check the latest updates and dependencies on the PCNtoolkit's GitHub [repository](https://github.com/amarquand/PCNtoolkit). Some of the tutorials require different versions of the PCNtoolkit. 


For additional helpful tips on setting up Google colab and using keyboard shortcuts, also see the ReadMe file for the [CPC course](https://github.com/predictive-clinical-neuroscience/PCNtoolkit-demo/tree/main/tutorials/Comp_Psych_Course).


When you are ready to run the analysis, you can launch the tutorial notebook by clicking the 'Open in Colab' button. You need to be signed in to a Google account in your internet browser and for best results, use Chrome web browser. 


**Normative Model Tutorial, ROI-level Cortical Thickness** contains the necessary commands for data extraction, preprocessing, formatting, visualization, quality checking, creating train/test splits, code for running the normative model on a few ROIs. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/predictive-clinical-neuroscience/PCNtoolkit-demo/blob/main/tutorials/ROI_blr_cortthick/NormativeModelTutorial.ipynb)

