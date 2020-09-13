# ML-Risky-Business
## Resampling 
Compared among Oversample (random sampling, SMOTE), Undersample (ClusteredCentroids) and Combination Sampling (SMOTEENN), we can conclude that...

1. Random Sampling method has the best accuracy score at 0.706 (for high risk prediction).

2. Clustered Centroids method has the best recall score at 0.66.

3. Both Random Sampling methods has the best geometric mean score at 0.70.

---
## Ensemble Learning

Using ensemble learning method (Balanced Random Forest and Easy Ensamble) on imbalanced data, we can conclude that...

1. Balanced Random Forest has the best accuracy score.

2. However, Easy Ensemble has the best recall score.

3. Both models have the same geometric mean score.

4. Top three importance features for credit risk are initial_list_status, out_prncp, and total_acc. These might be initial list status, current outstanding pricipal of loan,  and total account. 

---
Note: I added "Charged Off" status into high risk category as some loans in the data have the status. Charged Off is loan for which there is no longer a reasonable expectation of further payments. 

