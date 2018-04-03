# predict

A series of notebooks exploring different Machine Learning methods from [Scikit-Learn](http://scikit-learn.org/stable/).

- in [Geoscience ML notebook 1](https://github.com/mycarta/predict/blob/master/Geoscience_ML_notebook_1.ipynb), I look at methods for checking, tidying, and visualizing a dataset.

- in [Geoscience ML notebook 2](https://github.com/mycarta/predict/blob/master/Geoscience_ML_notebook_2.ipynb), I showcase some inferential statistics tools I built for selecting featues.

- in [Geoscience_ML_notebook 3](https://github.com/mycarta/predict/blob/master/Geoscience_ML_notebook_3.ipynb), I show how to use the prediction interval of a regression to discuss drilling economic risk.

- in [Geoscience_ML_notebook 4](https://github.com/mycarta/predict/blob/master/Geoscience_ML_notebook_4.ipynb), I take a quick look at what a simple neural network can learn about drilling problems due to mud loss.

- Geoscience ML notebook 5 will be a visual Support Vector Machines tutorial.

- in Geoscience ML notebook 6, I will evaluate and compare the performance of different ML methods in predicting a geophysical log from a suite of other logs; I was thinking of the compressional sonic initially, but I am now more keen on predicting the shear sonic. The log suite is from the same well (from Pev Avseth PhD Thesis) that Alessandro Amato del Monte used in the 
[Seismic Petrophysics Notebook](https://github.com/seg/tutorials/blob/master/1506_Seismic_petrophysics_2/Seismic_petrophysics_2.ipynb) accompanying his [Geophysical tutorial](http://library.seg.org/doi/abs/10.1190/tle34040440.1) article on The Leading Edge.

- in Geoscience ML notebook 7, I will summarize my experience in team with with [Mark Dahl](https://github.com/dahlmb) at the [SEG 2016 Machine Learning contest](https://github.com/seg/2016-ml-contest).



 To wet your appetites, here's an example of compressional sonic log prediction using a cross-validated linear model, which will be the benchmark to evaluate the performance of other models in notebook 3, such as SVM and Random Forest:

![linear](https://github.com/mycarta/predict/blob/master/images_4_README/linear_model.png)

and below is a heatmap with the pairwise Spearman correlation coefficient between the logs I will use:
 
![heat](https://github.com/mycarta/predict/blob/master/images_4_README/heatmap.png)


