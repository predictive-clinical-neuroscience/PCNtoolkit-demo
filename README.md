# Normative modelling demo with PCNtoolkit
This repository contains tutorials on normative modelling using public (multi-site) datasets. 

<div>
<img src="data/NormModelSetup.png" width="500"/>
</div>


`tutorials/` --> Contains the Python notebooks for the tutorials. 2020 virtual computational psychiatry course tutorial and a tutorial using Bayesian linear regression (blr) with ROI-level cortical thickness data extracted from the Killiany/Desikan parcellation atlas.

`data/` --> Contains the data used in the tutorials.

We will be running all of our code in Google Colab python notebooks. These are essentially Jupyter notebooks run in the :cloud: *cloud* :cloud:. 
Running our code using Colab will save us from dealing with python library installation and virtual environment setup. 

We will also be using the Pandas library for a lot of our code. There is a great intro to Pandas Colab notebook here: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/notebooks/mlcc/intro_to_pandas.ipynb)

Other helpful links if you are new to using the Pandas python library:
1. [Pandas cheatsheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)
2. [Pandas Selecting/Indexing API](https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html)
3. [Short (software carpentry) pandas tutorial 1](https://swcarpentry.github.io/python-novice-gapminder/07-reading-tabular/index.html)
4. [Short (software carpentry) pandas tutorial 2](https://swcarpentry.github.io/python-novice-gapminder/08-data-frames/index.html)


When you are ready to run the analysis, you can launch the notebooks below by clicking the 'Open in Colab' button. You need to be signed in to a Google account in your internet browser and for best results, use Chrome web browser. 
We have split the ROI-level cortical thickness tutorial into two parts:


**NormativeModelTutorialPart1** contains the necessary commands for data extraction, preprocessing, formatting, visualization, quality checking, creating train/test splits, etc. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/predictive-clinical-neuroscience/PCNtoolkit-demo/main/tutorials/ROI_blr_cortthick/NormativeModelTutorialPart1.ipynb)


**NormativeModelTutorialPart2** contains the code for running the normative model. If you wish to skip learning about data prep, you may go directly to notebook part 2. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/predictive-clinical-neuroscience/PCNtoolkit-demo/main/tutorials/ROI_blr_cortthick/NormativeModelTutorialPart2.ipynb)

**NormativeModelTutorialPart3** coming soon...contains code for visualization of models.