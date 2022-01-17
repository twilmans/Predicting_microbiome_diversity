# Predicting_microbiome_diversity
Different code examples written in Python for performing ML analysis from the paper ["Blood metabolome predicts gut microbiome α-diversity in humans"](https://www.nature.com/articles/s41587-019-0233-9)

The data analyzed in the study requires submission of a research plan, please see the original paper for details.
1) LASSO IMPLEMENTATION: trains a LASSO model using 10-fold CV to predict Gut Microbiome diversity, extracts key features, and evaluates model performance.
2) RF_CLASSIFIER: trains a random forest classifier with unbalanced number of cases and controls using a 10-fold CV scheme to identify individuals with depleted microbiome diversity, automatically calculates key performance metrics.
