COVID-19 (Coronavirus Disease-19), a disease caused by the SARS-CoV-2 virus, has been declared as a pandemic by the World Health Organization on March 11, 2020. Over 15 million people have already been affected worldwide by COVID-19, resulting in more than 0.6 million deaths. Protein-protein interactions (PPIs) play a key role in the cellular process of SARS-CoV-2 virus infection in the human body. Recently a study has reported some SARS-CoV-2 proteins that interact with several human proteins while many potential interactions remain to be identified. In this study, we aim to predict these potential interactions using Machine learning methods. We implemented classification algorithms like SVM, Random Forests, Decision trees and XGBoost. 

The problem has been posed as a two-class classification problem, where the two classes correspond to the interacting and non-interacting proteins of the virus and the host, respectively. 

All the algorithms were fairly successful to perform predictions on the test dataset. The model score is as follows-
1.)	Decision trees 99.04%;
2.)	Random Forest 97.11%;
3.)	Gradient boosting by XGBoost 94.84%;
4.)	SVM 68.04%;
Decision trees performed the best among all others.

In this study, various sequence-based features and computational approaches are used in predicting the potential human targets of the SARS-CoV-2 virus. Therefore, it can be assumed that SARS-CoV-2 is a virus expected to have a large number of interactions with human proteins. However, due to the lack of experimentally validated SARS-CoV-2-human PPIs, most of the possible interactions are currently unknown.
