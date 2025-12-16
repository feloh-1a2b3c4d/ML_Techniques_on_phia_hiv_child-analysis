# ML_Techniques_on_phia_hiv_child-analysis

# INTRODUCTION
Human immunodeficiency virus (HIV) is a virus that targets T helper cells, also known as CD4 cells, which are specific immune system cells when it infects a person. The virus multiplies and gradually destroys the cells that it calls home, weakening the body's defenses against infections. Sexual contact with injectable drugs, sharing needles among injectees, blood transfusions, and mother-to-child transmission (MTCT) through breast milk or before or during delivery are the main ways that HIV is spread. HIV infection is a widespread, sexually transmitted illness that affects all ages and genders in Kenya. It is mostly driven by sexual activity. There were 660,000 children listed as AIDS orphans as of 2015. Nonetheless, members of important communities have an abnormally high rate of new infections. According to estimates from 2020, these groups account for 30% of all new HIV infections in Kenya each year.

**General Objective**
> To identify and analyze the child HIV status in Kenya linking with demographic, socio-economic, and health-related factors.

**Specific Objectives**
>> To assess the strength and direction of the risk factors on the HIV status of children.
>> To evaluate the influence of socio-economic factors, including urbanization and wealth quintile, on the HIV status of children.
>> To identify which ML model is the best in predicting child HIV status.
>> To determine the relationship between demographic factors (such as age and gender) and the HIV status of children in Kenya.


**SIGNIFICANCE OF THE STUDY**
>> The study aims to bridge the knowledge gap by assessing the various predictors that can likely be the most risk factors contributing to the final HIV status of a child.
>> The study lies in its potential to inform healthcare experts on advising parents and households on precautions and measures in handling children in relation to HIV status like infected individual to enroll to medication and frequent health consultation, regular exercise and healthy diet to prevent the progression of other HIV related complications.
>> The study also Contribute to academic knowledge by providing statistical evidence by utilizing statistical test in studying the provided predictor variables.

**RESULTS**

**Strength and direction of the risk factors on the HIV status of children.**
Used Spearman rank test to assess the strength and direction of the explanatory variables with the response variable, using the output we found that Pedtri90 tend to have a perfect correlation with HIV status of a child.

**socio-economic and demographic factors influence on HIV status of a child**
Using the P-values to test the significance of the variables in predicting the HIV status of a child, it’s found out that variable’s momsick, dadsick, ch_kidhivtestevr, ch_kidvisttbclin, ch_kiddiagtb and pedtri90 tend to have a significant P-value in determining the final HIV status of a child. Variable’s momalive and dadalive had single recorded values thus did not compact the dichotomous response variable which led to a N/A P-value. 

**Machine Learning models implemented in the classification task**
From the Supervised ML models,  used SVM and Random Forest algorithm to solve the classification task and found out that SVM algorithm tended to be the best model in predicting cases of HIV status in a child basing on the metric accuracy score.

<img width="843" height="164" alt="image" src="https://github.com/user-attachments/assets/74a81a9a-25ed-482e-8bdf-42c29d6b1111" />
