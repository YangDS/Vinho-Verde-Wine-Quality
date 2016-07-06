# Vinho-Verde-Wine-Quality
This projects demos how to use R for analyzing the wine quality data (https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/) using linear regression, logistic regression, random forest, and other clustering algorithms. 

1. Sources

Created by: Paulo Cortez (Univ. Minho), Antonio Cerdeira, Fernando Almeida, Telmo Matos and Jose Reis (CVRVV) @ 2009

You can find the actual datasets at 
https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/
   
2. Summary

The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult: http://www.vinhoverde.pt/en/homepage or the reference [Cortez et al., 2009] (preprint). Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

Your goal is to analyze the relationship between the measurements taken on the wine and the stated wine quality on behalf of the Vinho Verde wine commission, which regulates the production of wine in that region of Portugal.  They have provided you with datasets of red and white wine, and posed several interesting questions (although your analysis should not be limited to these):

-	What measurements are important in determining the quality of a wine? How much can we learn about quality from these measurements?
-	Are there any groups of wines that seem similar in composition and resulting quality?
-	How can we use this data to predict truly exceptional (or poor) wines? How should we use this information?

As the commission is composed of technical (ie, chemists and agricultural scientists) and non-technical (farmers, government employees) members, your results should include both the technical details as well as summary of the results for the non-technical audience.

3. Notes

The two datasets were created using red and white wine samples. The inputs include objective tests (e.g. pH values) and the output is based on sensory data (median of at least 3 evaluations made by wine experts). Each expert graded the wine quality between 0 (very bad) and 10 (very excellent).  Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

4. Number of Instances: red wine - 1599; white wine - 4898. 

5. Number of Attributes: 11 + output attribute
  
   Note: several of the attributes may be correlated, thus it makes sense to apply some sort of
   feature selection.

6. Attribute information:
   
   Input variables (based on physicochemical tests):
   1 - fixed acidity
   2 - volatile acidity
   3 - citric acid
   4 - residual sugar
   5 - chlorides
   6 - free sulfur dioxide
   7 - total sulfur dioxide
   8 - density
   9 - pH
   10 - sulphates
   11 - alcohol
   Output variable (based on sensory data): 
   12 - quality (score between 0 and 10)



