# Sampling
## Dataset
The dataset used in this project is https://github.com/AnjulaMehto/Sampling_Assignment/blob/main/Creditcard_data.csv which is an imbalanced data-set.

## Objectives
The objectives of this project are:<br>
To balance the class distribution of the data-set<br>
To create five samples of the data-set using the sample size detection formula<br>
To apply five different sampling techniques on five different ML models<br>
To determine which sampling technique gives higher accuracy on which model<br>

## Methodology
The project is divided into three main steps as follows:

1. Balancing the Data-Set:<br>
In this step, we balanced the class distribution of the data-set using oversampling.

2. Creating Five Samples:<br>
We created five samples of the data-set using the sample size detection formula 
<b>n=(Z^2xpx(1-p))/(E^2)</b><br>
where, Z=1.96 (assumed)<br>
       p=0.5 (assumed)<br>
       E=0.05 (assumed)<br>
The following five sampling techniques were used:<br>
i) Simple Random Sampling<br>
ii) Stratified Sampling<br>
iii) Systematic Sampling<br> 
iv) Cluster Sampling<br> 
v) Convenience Sampling<br>

3. Applying Five Different Sampling Techniques on Five Different ML Models
In this step, we applied five different samples on five different ML models and compare their performance on the balanced data-set. The following models are being used:<br>
i) Logistic Regression<br>
ii) Decision Tree Classifier<br>
iii) Naive Bayes<br>
iv) Support Vector Machines (SVM)<br>
v) K-Nearest Neighbors (KNN)<br>
For each model, we will evaluate the performance using the accuracy given by them.

## Final Result Table<br>

|                        | Simple Random | Stratified |Systematic  | Cluster  | Convenience |
| ---------------------- | ------------- | ---------- | ---------- | -------  | ----------- |
| Logistic Regression    |0.8448         |0.9260      |0.8936      |0.9560    |0.8701       |
| Decision Tree          |0.9827         |0.9955      |1.0000      |0.9898    |0.9826       |
| KNN                    |0.9655         |0.9955      |0.9787      |0.9932    |1.0000       |
| SVC                    |0.6206         |0.6950      |0.7234      |0.7500    |0.7445       |
| Gaussian NB	           |0.6206         |0.7937      |0.7234      |0.6959    |0.7532       |

## Results
In the final step, we analyzed the results and determined which sampling technique gives higher accuracy on which model.

## Conclusion
This project provides a comprehensive methodology for balancing an imbalanced data-set using various sampling techniques and comparing the performance of different ML models on the balanced data-set.

## Writtten by<br>
Submitted by-Avneet kaur<br>
Roll no-102003487<br>
Group-CO20<br>
