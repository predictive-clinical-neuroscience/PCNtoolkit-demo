# The Normative Modeling Framework for Computational Psychiatry

For this tutorial we will use data from the [Human Connectome Project Young Adult study](https://www.humanconnectome.org/study/hcp-young-adult) and [IXI](https://brain-development.org/ixi-dataset/) to create a multi-site dataset. For using these data we follow the original open access data use agreements for these studies, described below. Please adhere to these data use terms. 

For HCP data you must have an account at ConnectomeDB and agree to the [Open Access Data Use Terms](https://www.humanconnectome.org/study/hcp-young-adult/data-use-terms). For the IXI data, it is made available under the Creative Commons CC BY-SA 3.0 license. If you use the IXI data please acknowledge the source of the IXI data, e.g. [this website](https://brain-development.org/ixi-dataset/).

This folder contains 5 python notebooks: 

1. BLR_normativemodel_protocol.ipynb --> contains the code that appears in the Procedure section of Rutherford et al. 2021, *The Normative Modeling Framework for Computational Psychiatry*. Accepted at Nature Protocols. Preprint available via [BioRxiv](https://www.biorxiv.org/content/10.1101/2021.08.08.455583v1).

2. visualizations.ipynb --> contains the code for creating various visualizations of normative modeling output metrics from Figure 4 of Rutherford et al. (2021)

3. post_hoc_analysis.ipynb --> example of using deviation scores as input features in a SVM classification framework. This notebook compares the results of using deviation scores as input features to the results of using the true raw data as input features. Also includes classical case vs. control testing on deviation scores and raw cortical thickness data. 

4. transfer_pretrained_normative_models.ipynb --> contains the code to apply pre-trained normative models from a lifespan big data sample (described in this [paper](https://elifesciences.org/articles/72904)) to new samples. Also contains the code to visualize the centiles of variation (Figure 4D).

4. other_predictive_models.ipynb --> contains code to run the other common brain-behavior predictive models mentioned in the 'Applications and Comparison with Other Methods' section of Rutherford et al. (2021). Uses deviation scores and raw cortical thickness data as input to the predictive models (regression framework).
