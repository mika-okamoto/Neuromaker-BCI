# Neuromaker-BCI

We built and fine-tuned machine learning models to classify studnet brain states and focus levels from EEG data using scikit-learn. We handled end-to-end data collection, cleaning, and analysis with pandas and matplotlib.

This is our code for our classifiers of three states of the brain - active, neutral, and meditate. We recorded samples of EEG data using the NeuroMaker BCI Crimson headbands for each state, removed outliers, normalized data, graphed data, trained data, feature selected, feature extracted, trained, tested, and cross-validated various classifiers. 


Classifier V1 was trained on only Daniel’s data, and performed well on the initial data set but poor on any new data. This led us to expand our domain of data for Classifier V2

Classifier V2 was trained on 14 people on Mr. Mauro’s AET class, each following a set data collection process. It performed much better on new data both from a person included in the training data and a person not in the training data set. 

Documentation: https://docs.google.com/document/d/16Qvu7PdplANfnyq18SzMBr-dEtlILa6plb45jD60njQ/edit#

See `Classifier_V2/classifier_v2.ipynb` for final pipeline, `Classifier_V2/ensemble_tuning.ipynb` for hyperparameter tuning and model testing, and `plot_folder.ipynb` for data visualization. 
