# Normative modelling demo with PCNtoolkit

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5592153.svg)](https://doi.org/10.5281/zenodo.5592153)

This repository contains tutorials on normative modelling using public (multi-site) datasets. 

<div>
<img src="data/NormModelSetup.png" width="500"/>
</div>


`tutorials/` --> Contains the Python notebooks for the tutorials. We currently have two tutorials available, the 2020 virtual computational psychiatry course tutorial and a tutorial using Bayesian linear regression (blr) with ROI-level cortical thickness data extracted from the Killiany/Desikan parcellation atlas.

`data/` --> Contains the data used in the tutorials. Data created during the cortical thickness ROI tutorial will be output into this folder. 

For this tutorial we will use data from the [Human Connectome Project Young Adult study](https://www.humanconnectome.org/study/hcp-young-adult), [CAMCAN](https://www.cam-can.org/), and [IXI](https://brain-development.org/ixi-dataset/) to create a multi-site dataset. For using these data we follow the original open access data use agreements for these studies, described below. Please adhere to these data use terms. 

For HCP data you must have an account at ConnectomeDB and agree to the [Open Access Data Use Terms](https://www.humanconnectome.org/study/hcp-young-adult/data-use-terms). For CAMCAN data please review and follow the data use agreement found [here](https://camcan-archive.mrc-cbu.cam.ac.uk/dataaccess/datarequest-nobutton.php). For the IXI data, it is made available under the Creative Commons CC BY-SA 3.0 license. If you use the IXI data please acknowledge the source of the IXI data, e.g. [this website](https://brain-development.org/ixi-dataset/).

We will be running all of our code in Google Colab python notebooks. These are essentially Jupyter notebooks run in the :cloud: *cloud* :cloud:. 
Running our code using Colab will save us from dealing with python library installation and virtual environment setup. 

We will also be using the Pandas library for a lot of our code. There is a great intro to Pandas Colab notebook here: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/notebooks/mlcc/intro_to_pandas.ipynb)

Other helpful links if you are new to using the Pandas python library:
1. [Pandas cheatsheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)
2. [Pandas Selecting/Indexing API](https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html)
3. [Short (software carpentry) pandas tutorial 1](https://swcarpentry.github.io/python-novice-gapminder/07-reading-tabular/index.html)
4. [Short (software carpentry) pandas tutorial 2](https://swcarpentry.github.io/python-novice-gapminder/08-data-frames/index.html)

For some helpful tips on setting up Google colab, also see the ReadMe file for the [CPC course](https://github.com/predictive-clinical-neuroscience/PCNtoolkit-demo/tree/main/tutorials/Comp_Psych_Course).

When you are ready to run the analysis, you can launch the notebooks below by clicking the 'Open in Colab' button. You need to be signed in to a Google account in your internet browser and for best results, use Chrome web browser. 


**Normative Model Tutorial, ROI-level Cortical Thickness** contains the necessary commands for data extraction, preprocessing, formatting, visualization, quality checking, creating train/test splits, code for running the normative model on a few ROIs. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/predictive-clinical-neuroscience/PCNtoolkit-demo/blob/main/tutorials/ROI_blr_cortthick/NormativeModelTutorial.ipynb)

