# predict

The idea is to predict a geophysical well log, the sonic, using a suite of other logs: depth, density, gamma ray, and neutron.

The log suite is from the same well (from Pev Avseth PhD Thesis) that Alessandro Amato del Monte used in the 
[Seismic Petrophysics Notebook] (https://github.com/seg/tutorials/blob/master/1506_Seismic_petrophysics_2/Seismic_petrophysics_2.ipynb) accompanying his
 [Geophysical tutorial] (http://library.seg.org/doi/abs/10.1190/tle34040440.1) article on The Leading Edge.
 
 I will explore different Machine Learning methods from [Scikit-Learn](http://scikit-learn.org/stable/). 
 
 Here's a heatmap with the pairwise Spearman correlation coefficient between the logs I will use:
 
![heat](https://github.com/mycarta/predict/blob/master/images_4_README/heatmap.png)

and below an example of sonic log prediction using a cross-validated linear model, which will be our benchmark for the performance of other models such as SVM and Random Forest:

![linear](https://github.com/mycarta/predict/blob/master/images_4_README/linear_model.png)


