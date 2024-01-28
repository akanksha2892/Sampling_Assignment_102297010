# Sampling_Assignment_102297010
Objective
The primary objective of this assignment is to address class imbalance in the provided dataset (Creditcard_data.csv) using various resampling techniques. The code focuses on implementing Random Under Sampling and evaluating the impact on five different machine learning models.
Models used are: Logistic Regression, Decision Tree Classifier, Random Forest Claassifier, Gradent boosting classifier, Support vector classifier

1. Data Preprocessing
   Initial Class Distribution
   The initial class distribution in the dataset is examined to identify potential class imbalance issues.

   Balancing the Dataset
   Random Under Sampling is employed from the imbalanced-learn library to address the class imbalance. This technique randomly removes instances from the majority
   class to create a more balanced distribution.

   Scaling Features
   The features of the resampled dataset are standardized using StandardScaler to ensure each feature has a mean of 0 and a standard deviation of 1.

2. Creating 5 Samples
   
   Sampling Sizes
   Five samples are generated with varying sizes ranging from 20% to 100% of the resampled dataset, providing a diverse set of training data sizes for model
   evaluation.
   
   Reproducibility
   A random state of 42 is set during the sampling process to ensure reproducibility, allowing the generation of the same samples in future runs.

4. Machine Learning Models
   
   Selected Models
   Five machine learning models are chosen for evaluation: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, and Support Vector Classifier
   (SVC).
   
   Model Training
   Each model is trained on the entire scaled resampled dataset. Note that, in practice, model training would typically be performed on the training set.
   
   Model Evaluation
   The trained models are evaluated on each of the five samples to observe the impact of varying sample sizes on model performance.

5. Results and Observations
   
   Accuracy Measurement
   Accuracy is chosen as the evaluation metric for its simplicity and interpretability. The accuracy of each model on each sample is calculated and printed.

   Interpretation of Results
   Results are interpreted, highlighting trends or patterns observed across different models and sample sizes.
