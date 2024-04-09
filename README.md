# Marketing-House-Predictions 
## Tax Appeal<br><br>
### Understanding Property Tax Appeal in Cook County<br>
* **Appeals Process**: Property owners can appeal their assessments, which may lead to revised assessments<br>
* **Industry Impact**: Inaccuracies in initial assessments have created a multimillion-dollar industry around tax appeals<br>
* **Unfairness Concerns**: The system may introduce opportunities for unfairness, influenced by factors such as race or median income<br>
* **Monetary Rewards**: Factors affecting the monetary rewards of appealing include the amount gained from a successful appeal<br><br>
These points align with the issues of transparency and fairness in the property tax system<br>

# Approach to address the two issues immediately below
* Factors that lead a property owner to appeal<br>
* Parts played by factors like race or median income<br><br>

Based on the surveys, voters believe that the property tax is the most unfair worst tax. Therefore the property owners was introduced to use appealling to reduced the assesed value. So here we use a bigger, enriched dataset in this project, this dataset consisting of 19036 properties that have sold in the three regions of Cook County (Northwest Suburban Cook County, Chicago, Southwest Suburban Cook County), among which 9018 properties appealled (47.4%), and the winning case is 5587, which mean the wining rate is 62%, overall CCAO and BOR granted 29% of those properties some reduction in their assesed values.
This dataframe contains 26 columns,and all 26 columns have missing value<br>
Remove Outliers( for min value is 50K, min squre foot is 300)<br>
Creation of a new column variable Appeal_1_0 to represent that property has appealled or not, we also add column Log_Value and Log_medhinc<br>

Some of these correlations may be driven by the fact that taxpayers self-select as to whether they appeal their taxes or not:<br>
First pass assessed value, property actual sale value (or Log_value) and squarefoot, median household income of the property owner, percentage of eligible adults in the property's census tract with a 4 year college degree and average school score are all positive correlated with the property owner would appeal or not, it shows high income, higher level of education and rich home owner has bigger posibility to make appeal, also regard to race,  white compare with other race has bigger posibility to make appeal.<br>
Also, many larger condominiums buildings can hire attorneys tofile appeals for all of the units in the building, taking advantage of the returns to scale in this type of appeal.Neighbours may share the information with each other, result in some neighborhoods having a very high rate of appeal, simply because of the compounding effect. Laywer may have target customer to encourage them file the appeal, this all realted to why high income, high educate and white people lead the appeal happen.<br>