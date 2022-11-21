Author: Suhasini Tatipalli

# House-Prices-Prediction

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

Business Problem: Predicting sales prices 

Cleaning the data involved creating an informative print report, viewing where my missing values for respective collumns were, and verifying there weren't any duplicates.
I then decided to explore feature engineering techniques Combining all area/Sqft columns, dropping and replacing with a "TotalArea"/"TotalSqft" column.

Neural Network model has a nice hockey-stick-shaped learning curve and the final training and testing scores are very similar. It does not seem to suffer from overfitting or underfitting. The R2 score shows that this model is explaining about 87% of the variance in the target, the mean absolute error shows that this model tends to make an error of about 181K saleprice, and since the root mean squared error is significantly higher than the mean absolute error, this shows us that it has made some larger errors on some samples.
