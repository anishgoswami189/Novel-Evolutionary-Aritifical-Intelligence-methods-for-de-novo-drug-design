# Novel-Evolutionary-Aritifical-Intelligence-methods-for-de-novo-drug-design
A 3 step proccess to generate possible drugs given a target
# Requirements
* Numpy
* DeepPurpose
* Rdkit
* Tensorflow
* TPU to train Classifier
# Notebooks
* Classifier_Inference.ipynb: Uses classifier to compute binding score of molecule and target of molecules ranked by optimizer
* Classifier_Training.ipynb: Trains classifier
* Data_Post_Proccessing.ipynb: Tests generated molecules for uniqueness, validity, drug-likeness, and how many are predicted to be active against malaria.
* Generator_Training.ipynb: Trains generator
* Generator_Inference.ipynb: Uses generator to generate 100000 molecules
* Optimizer_Non-dominated_sorting.ipynb: Uses non dominated sorting algorithim to rank generated molecules by drug likeness and choose 75,000 best
# Data
* bindingscores: containes the binding scores of each ranked molecule to malaria
* generated_molecules: 500 generated molecules to test Generator's abilities
* ranked_molecules: 75000 most drug-like molecules ranked by optimizer

