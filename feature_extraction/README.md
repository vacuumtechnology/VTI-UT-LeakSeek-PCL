# Feature Extraction

The code is written in Python in a Jupyter Notebook. The following libraries are required: matplotlib, numpy, pandas.

The code reads in a point cloud data file (PCD) and plots the data in a 3D scatter plot. The code also extracts several features, namely the four types of "joints" that are of interest. This extraction was completed by manually observing the ranges of x, y, and z values for each "joint" type example, taking all PCD points within those ranges, then saving these filtered points as a separate PCD file. Additionally, each extraction is visualized to ensure the areas of interest are successfully extracted.

Note: "mat" in "feature-mat" stands for "material change." Please reference the Jupyter Notebook for a visualization of what a "material change" looks like.