# Feature Detection

The code is written in Python in a Jupyter Notebook. The following libraries are required: matplotlib, numpy, pandas, opencv, scipy

## Files
- `point_cloud_to_img.ipynb` converts a pcd file into a 2D image. Note: The pcd file is converted to a txt file with a single header "x y z rgb" before the data prior to this conversion.
- `vectorized_feature_detection.ipynb` contains the initial feature detection code that vectorizes the manifold/reference feature and uses the naive difference comparison method.
- `vectorized_pattern_feature_detection.ipynb` contains the updated feature detection code with more sophisticated comparison methods that achieves 100% T-joint detection.
- `vectorized_color_feature_detection.ipynb` contains color segmentation code used to find the material change feature.
- `manifold_alignment.ipynb` contains code to automatically rotate an input manifold image to match the orientation of a reference manifold image required for the feature detection algorithm.
- `automatic_manifold_alignment.ipynb` was an attempt at automatically rotating an input manifold image without any needed reference manifold image. The idea was to use the general orientation of the aluminum portion and rotating that orientation to a horizontal position. [Work In Progress]