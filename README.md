# Breast-Cancer-Analysis

> ## Idea-
Information and Communication Technologies (ICT) can play potential roles in cancer care. In fact, Big data has advanced not only the size of data but also creating value from it; Big data, that becomes a synonymous of data mining, business analytics and business intelligence, has made a big change in BI from reporting and decision to
prediction results4. Data mining approaches, for instance, applied to medical science topics rise rapidly due to their high performance in predicting outcomes, reducing costs of medicine, promoting patients  health, improving healthcare value and quality and in making real time decision to save people's lives.
Early diagnosis of breast cancer is important for its successful treatment. Therefore,there is a requirement for accurate and cheap diagnostic methods. In this project we aim at exploring the applicability of decision tree machine learning techniques like Support Vector Machine(SVM),Classification and Regression Tree(CART), K-Nearest Neighbours(KNN) and Random Forest for breast cancer diagnosis using proteomic data to predict the class of the cancer. Besides we have also predicted the probability of survival using the above mentioned machine learning algorithms. 
Further we have ensembled the algorithms by stacking them to improve accuracy of the prediction.

> ## Implementation-
### Classification:
We have mainly used four machine learning algorithms to achieve our objective.The algorithms used are listed below-
1. SVM
2. CART
3. KNN
4. Random Forest

The accuracy obtained in the above models is listed below-
* SVM	84.7%
* CART	57.1%
* KNN	90.5%
* Random Forest	85.7%

### Predicting Vital Status:
We have six algorithms to achieve our objective.Besides using single algorithms to predict the Vital Status we have also ensemble the algortihms by stacking them in layers to improve the accuracy. Stacking is an ensemble learning technique that combines multiple classification or regression models via a meta-classifier or a meta-regressor. The base level models are trained based on a complete training set, then the meta-model is trained on the outputs of the base level model as features.We have used Linear Discriminant Analysis, Random Forest and Generalised Linear Model(GLM) as the base level models and Generalised Boosted Regression Model(GBM) and SVM-linear as meta models.

The accuracy obtained are listed below-
* GLM	84.21%
* LDA	84.21%
* Random Forest	89.47%
* Stacking(Meta-Model :GBM)	89.47%
* Stacking(Meta-Model :SVM Linear)	94.74%
