# insurance

Context: You are a data scientist in the car insurance area of an insurance company. Attached is a dataset βCaseStudyDatasetQ.csvβ that contains data related to the historical car accident claims received by your company.

The dataset contains feature vector π = (π₯1, π₯2, π₯3, π₯4, π₯5) where:
β’ π₯1 refers to car weight: weight; 
β’ π₯2 refers to annually driven distance: distance; 
β’ π₯3 refers to age of driver: age; 
β’ π₯4 refers to age of car: carage; 
β’ π₯5 refers to gender of driver: gender;

In addition to feature vector ππ, the data includes volume: π£π (exposure) and claims count (Counts) ππ~ππππ π ππ(π£ππ(π₯π)) for a portfolio of car insurance policies π = 1, β¦ , π.

Requirement:
Draft a technical report to your manager outlining an approach to predicting the claims frequency of this portfolio. Consider the following tasks:

1. Perform exploratory data analysis on the dataset including a. Data checks b. summary statistics of the variables c. any relationships between the variables including any visualisations d. any hypothesis based on these relationships
2. Estimate π(π) assuming linear terms in π₯1, β¦ , π₯5, quadratic terms in π₯1 2,β¦ , π₯5 2 and
mixed terms π₯1π₯2, π₯1π₯3, π₯1π₯4, π₯2π₯3, π₯2π₯4, π₯3π₯4. Select the best model.
3. Estimate π(π) using Poisson regression tree, including in your commentary the optimal size of the tree.
4. Estimate π(π) using Poisson boosting tree method (with no base model), including in your commentary the number of boosting steps and the size of the tree
5. Compare the models fitted in (2-4) and any other model you choose using 10-fold cross validation error to select the best model
Summarise your results and findings in a technical report of 1-2 pages in length covering: background, methodology and approach for model selection and results.
Include an appendix to hold
1. Any analysis you have conducted that you would like to share outside of the body of the report as Appendix A
2. Your code created for the analysis as Appendix B Submit both your report and any code created.
