README: Machine Learning and Data Mining Report



**1. Obesity Classification Using Lifestyle Data**  

In this project, I designed an end-to-end machine learning workflow to predict obesity levels based on individual lifestyle, dietary habits, and physical activity, using a dataset from Latin American countries.
Key steps included:

EDA & Preprocessing: Visualized class distributions, encoded variables, and handled class imbalance using SMOTE.

Feature Engineering: Applied Variance Thresholding and Recursive Feature Elimination (RFECV) with a Random Forest base model.

Modeling (Python): Trained Decision Tree and KNN models, with hyperparameter tuning to boost performance.

Results: Best model (Decision Tree) achieved 97.6% accuracy.

Tools Used: Python (Scikit-learn, Pandas), SMOTE, RFECV, GridSearchCV.	


**2. Customer Segmentation Using Clustering Techniques** 

This project aimed to uncover patterns in customer demographics, spending, and marketing engagement to enable targeted strategies through unsupervised learning.

Data Processing: Handled nulls, recoded categorical features, aggregated variables (total spend, web visits, etc.), and computed customer age.

Dimensionality Reduction: Applied PCA for feature compression and 2D visualization.

Clustering Techniques:

K-Means Clustering: Optimal k = 3 (via Elbow method). Achieved silhouette score of 0.47, indicating moderate cohesion.

Hierarchical Clustering: Optimal clusters = 4 (via dendrogram). Silhouette score of 0.31, suggesting overlapping clusters.

Insights: Segments primarily differed by income and spend. Provided recommendations for targeted campaigns.

Tools Used: Python (Sklearn, Pandas, Matplotlib), PCA, VarianceThreshold, Silhouette Analysis.


**3. Steam Game Review NLP: Constructiveness & Sentiment Analysis**  

In this NLP-focused project, I explored Steam reviews of the top 10 most-reviewed games to determine review quality and sentiment.

Text Preprocessing: Used tokenization, stopword removal, and stemming (Porter) to clean the review text.

Constructiveness Classification:

Model: Multinomial Naive Bayes trained on Bag-of-Words vectors.

Handling Imbalance: Used SMOTE post-split.

Optimization: GridSearchCV tuning boosted accuracy to 75%.

Evaluation: High precision (0.88) for non-constructive reviews, recall (0.85) for constructive ones.

Sentiment Analysis:

Applied VADER for polarity scoring and classification.

Discovered game-specific sentiment trends (e.g., Terraria had 72% positive sentiment; PUBG had 52% negative).

Generated word clouds for positive and negative feedback.

Tools Used: Python (NLTK, Scikit-learn, VADER), SMOTE, GridSearchCV, WordCloud.
