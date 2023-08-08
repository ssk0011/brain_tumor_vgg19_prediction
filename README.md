# brain_tumor_vgg19_prediction
Inspired by testing VGG19 on a brain tumor dataset for feature extraction against logistic regression. The goal was to see whether a simpler model could handle a reduced feature space using this extraction method.

# Initial Takeaways

Surprisingly, logistic regression with only 100 components in the feature space was able to achieve 81% accuracy, without a fully exhaustive grid search. This also implies that achieving an explained variance higher than 90% in PCA may not be required for a reliable predictions.

# Future Work

Expand models to include XGBoost, LightGBM, and a neural network implementation. Compare run times and accuracy for each to understand which is most efficient while still provide strong results.