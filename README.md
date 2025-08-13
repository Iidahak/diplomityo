# Master's Thesis

Source code for my MSc thesis on "Tree species classification using phenological patterns in multitemporal Sentinel-2 data under class imbalance".

Abstract: 

This thesis studies the optimal pipeline for accurately mapping tree species in an imbalanced dataset. We train and compare two
models: Random Forest and Multilayer Perceptron in classifying tree species from a
combination of S2 imagery with Light Detection and Ranging data. Both models are
evaluated with and without oversampling and algorithm-level balancing strategies. Furthermore, we aim to capture the phenological variation
in tree species provided by the S2 timeseries using two sets of input features: the
raw reflectance values and phenology-derived features. 

The results indicate that the deep learning approach (MLP) achieves better performance
than RF in tree species classification. Balancing methods significantly improved minority class detection across both models
and input data types, with improvement observed regardless of the method used.
Furthermore, S2 time series data provided only small improvements to the
classification compared to the lidar-only inputs, suggesting limited added value from
the spectral information in this setting.



