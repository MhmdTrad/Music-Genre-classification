# Music-Genre-classification
 The task was to classify and predict the categories of music and songs based on several characteristics related to them.

 before feeding the dataset into the model, I performed a series of operations on the data called "Data preparation and exploration," which is a crucial stage. These operations included:

Discovering and understanding the data: I analyzed the dataset by looking at the features and their types to get a broad understanding of the data.

Data preprocessing: This is the most important stage and has a direct impact on the performance of the model. Some of the actions I took to improve accuracy included dropping irrelevant columns, checking for duplicate values, visualizing the data, handling missing values, applying a boxcox transform to handle skewed columns, implementing SMOTE to handle imbalanced data, also data scaling and selecting features using SelectKBest.


The final stage involved building a model to predict the classes in the dataset. I experimented with several algorithms, including LazyClassifier, LGBMClassifier, XGBClassifier, RandomForestClassifier, ExtraTreesClassifier, GradientBoostingClassifier, and votingClassifier, and others.

I obtained the highest f1_score using the extra tree classifier, which had an f1_score of 0.77. The random forest classifier also performed well, with an f1_score of 0.75.
