Prediction of cervical cancer using machine learning methods

Introduction:

Cervical cancer is the fourth most common cancer among women worldwide, with around 660,000 new cases in 2022, according to the WHO. It is caused by the Human Papillomavirus (HPV), a sexually transmitted infection. Prediction of cervical cancer can be done at early stages by diagnostic tests like Hinselmann test, Schiller test, Cytology test, pap-smear test, biopsy, and other screening tests. Diagnosis of cervical cancer includes several challenges such as, late detection, limited access to screening tests, and variability in quality of screening.


Work description:

In this project, various machine learning models were evaluated for predicting cervical cancer. Three methodologies were developed for this purpose. The dataset, gathered from ' Universitario de Caracas' (UCI) was pre-processed, and due to its imbalanced nature, oversampling  technique was employed.  In Methodology 1, SMOTE was utilized, followed by the application of various classification algorithms such as Decision Trees, Random Forest, KNN, and Logistic Regression. Most of the algorithms underperformed, but Decision Trees and Random Forest delivered comparatively better results, which led to the employment of various optimizations on these algorithms. Relevant features were then selected, and recursive feature elimination techniques were applied to these two, yielding better results. However, the recall scores remained low, prompting the implementation of hyperparameter tuning. Furthermore, ensemble learning techniques, with the base learner as Decision Tree, were applied. Methodology 2 employed the AdaBoost classifier to further enhance prediction accuracy. However, the proposed model, the XGBoost classifier, outperformed all other models, delivering the best results. XGBoost's robust performance in terms of accuracy and recall made it the top-performing model for cervical cancer prediction.
