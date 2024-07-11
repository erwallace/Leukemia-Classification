# leukemia-classification

## Slimming Down the Gene Pool: A Lean Approach to Leukemia Classification

This study examines dimensionality reduction techniques to address the "curse of dimensionality" in genetic microarray datasets, which often have far more features than samples. We compare feature selection and extraction methods for reducing dimensionality while maintaining classification accuracy. A Support Vector Machine classifier achieved 100\% accuracy on the test set using all features. We found that Recursive Feature Addition (RFA) required only 3 features to maintain perfect accuracy, outperforming standard feature extraction methods like Principal Component Analysis. Our results suggest that for applications requiring model interpretability, such as cancer research, feature selection methods can match or exceed the performance of feature extraction while preserving feature meanings.

All code used for the analysis and plots generated is available in the `leukemia-classification.ipynb` notebook.
