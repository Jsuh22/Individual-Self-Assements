# Individual-Self-Assements

I main task was database. Which was fairly simple because of the data that we selected already being quite clean. The only major thing I had to figure out was doing a UNION between our two data sets. Which after googling was very simple.
As a team we all did our parts and beyond. If anyone needed help on something and asked we would chip in. It felt like a group effort and we had no conflicts.

# Summary

For this project we aim to assess wine quality, and whether it is possible to classify a wine based on its chemical properties. 

## **Question 1**:
Is a "Good" wine able to be predicted via the analysis of a wine's physicochemical properties? 

- Moderately so, an algorithm can predict a good wine.
  - Logistic Regression was able to output an accuracy score of 71%
  - Random Forest scored an F1 of 69%
    - Recall: 69%
    - Precision: 72%

## **Question 2**:
What physicochemical features are most responsible for determining wine quality?

- Based on Random Forest feature importance rankings, the following three provided the most value:
  - Alcohol (0.17)
  - Volatile Acidity (0.11)
  - Density (.11)

## **Question 3**: 
Can a 'good' wine be predicted using a chemical analysis agnostic of wine type (red or white)?

- Yes - interestingly, wine type was the least important feature by a large amount.
