Thyroid disease is a common cause of medical diagnosis and prediction, with an onset
that is difficult to forecast in medical research. The thyroid gland is one of our body's
most vital organs. Thyroid hormone releases are responsible for metabolic regulation.
Hyperthyroidism and hypothyroidism are one of the two common diseases of the thyroid
that releases thyroid hormones in regulating the rate of body's metabolism.
The main goal is to predict the estimated risk on a patient's chance of obtaining thyroid
disease or not.

Methodology used for analysis and prediction:
1) Matplotlib and seaborn for effective visualisation and data set analysis(box plot, scatter plot, correlation plot,countplot,etc). D-Tale was imported in order to perform in depth data analysis and a detailed visualistaion.
2) Dimensionality reduction
3) KNN Imputation for replacing missing values, n_neighbors was set to 5
4) Random over sampling to redistribute the data points in the class column, to reduce biasness
5) Label encoding, mapping and creating a dummy variable for converting str values to int/float
6) Algorithms for making predictions were : XGBoost, Decision Tree classifier, Support Vector Classifier
7) Decision Tree Classifier was the most accurate (99.6%)
8) Confusion matrix was plotted for the same
