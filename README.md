# Parkinson's Disease Detection using Voice Data
Voice disorder dataset can be used to detect the presence of Parkinson's disease in an individual. While current tools have limitations in analyzing complex voice disorders, advancements in technology and research have enabled the development of new algorithms that can identify specific acoustic markers associated with Parkinson's disease in voice recordings. Therefore, the analysis of voice disorders can provide valuable information in diagnosing and monitoring Parkinson's disease.

This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD). Our dataset includes voice attributes Information that can be used for detecting parkinson, these information including:

Matrix column entries (attributes):

name - ASCII subject name and recording number
MDVP:Fo(Hz) - Average vocal fundamental frequency
MDVP:Fhi(Hz) - Maximum vocal fundamental frequency
MDVP:Flo(Hz) - Minimum vocal fundamental frequency
Five measures of variation in Frequency
MDVP:Jitter(%) - Percentage of cycle-to-cycle variability of the period duration
MDVP:Jitter(Abs) - Absolute value of cycle-to-cycle variability of the period duration
MDVP:RAP - Relative measure of the pitch disturbance
MDVP:PPQ - Pitch perturbation quotient
Jitter:DDP - Average absolute difference of differences between jitter cycles
Six measures of variation in amplitude
MDVP:Shimmer - Variations in the voice amplitdue
MDVP:Shimmer(dB) - Variations in the voice amplitdue in dB
Shimmer:APQ3 - Three point amplitude perturbation quotient measured against the average of the three amplitude
Shimmer:APQ5 - Five point amplitude perturbation quotient measured against the average of the three amplitude
MDVP:APQ - Amplitude perturbation quotient from MDVP
Shimmer:DDA - Average absolute difference between the amplitudes of consecutive periods
Two measures of ratio of noise to tonal components in the voice
NHR - Noise-to-harmonics Ratio and
HNR - Harmonics-to-noise Ratio
status - Health status of the subject (one) - Parkinson's, (zero) - healthy
Two nonlinear dynamical complexity measures
RPDE - Recurrence period density entropy
D2 - correlation dimension
DFA - Signal fractal scaling exponent
Three nonlinear measures of fundamental frequency variation
spread1 - discrete probability distribution of occurrence of relative semitone variations
spread2 - Three nonlinear measures of fundamental frequency variation
PPE - Entropy of the discrete probability distribution of occurrence of relative semitone variations

![image](https://github.com/user-attachments/assets/99a30f3e-2bea-430a-9904-56779040c2b9)

t-SNE (t-Distributed Stochastic Neighbor Embedding) is a machine learning technique used for dimensionality reduction and visualization of high-dimensional datasets. It is particularly useful for visualizing complex data structures, as it helps to project the data points from a high-dimensional space to a lower-dimensional space (usually 2D or 3D) while preserving the relationships between the data points as much as possible.
![image](https://github.com/user-attachments/assets/66e1f713-00ac-4f80-9de8-b480d3a6c657)

**k-Nearest Neighbors (k-NN)**
In k-NN, the basic idea is to predict the label of a new instance based on the labels of its k nearest neighbors in the training data.
![image](https://github.com/user-attachments/assets/433bd6ca-a9aa-4ed1-b49c-b44c40d45304)

Classification Report:
               precision    recall  f1-score   support

           0       0.64      0.75      0.69        12
           1       0.93      0.89      0.91        47

    accuracy                           0.86        59
   macro avg       0.79      0.82      0.80        59
weighted avg       0.87      0.86      0.87        59


Accuracy Score: 0.864406779661017

**GridSearchCV**
Hyperparameter tuning is done to increase the efficiency of a model by tuning the parameters of the neural network. Some scikit-learn APIs like GridSearchCV and RandomizedSearchCV are used to perform hyper parameter tuning. 

Best Parameters:  {'n_neighbors': 9}
Best Score:  0.97

recall score on the test data using the predicted labels: 0.9148936170212766

**KNeighborsClassifier()**
Confusion matrix, without normalization
[[ 32  16]
 [  5 142]]
 ![image](https://github.com/user-attachments/assets/da33627b-8691-42cc-95dc-dbbb16bd52fc)

**Machine Learning Interpretability** 
Machine learning interpretability refers to the ability to understand and explain how a machine learning model arrives at its predictions or decisions.

![image](https://github.com/user-attachments/assets/da1691ae-74d1-4965-85ab-f01904e65702)
