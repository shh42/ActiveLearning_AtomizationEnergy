Title: Using Active Learning(uncertainty sampling) to Build a Model Predicting Atomization Energy from Molecular Fingerprints
<br><br>Author: Shengping Huang, Aojie Li, Jinbo Long, and Chi Zhang
<br><br>Description: Using 300 molecular data from QM7 dataset, we build a gaussian process regression model to predict atomization energy. We want to use as little data points as possible to train the model but, at the same time, having better accuracy. So we implant the idea of active learning in the process of building the model. Taking advantage of the natural returned standard deviation from the gaussian process  regression model, we are able to use max uncertainty method to find the datapoint the model most uncertain about, then teach it to the model.
<br><br>"Final_project.ipynb" is the process to build and validate the model.
<br>"test.ipynb" compares the performance using active learning(max uncertainty method) with ramdom sampling.(graph in the bottom)
