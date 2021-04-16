# EDA-on-Ashrae-Energy-Prediction

#### An overview of the problem statement from Kaggle

Q: How much does it cost to cool a skyscraper in the summer?
A: A lot! And not just in dollars, but in environmental impact.

Thankfully, significant investments are being made to improve building efficiencies to reduce costs and emissions. The question is, are the improvements working? That’s where you come in. Under pay-for-performance financing, the building owner makes payments based on the difference between their real energy consumption and what they would have used without any retrofits. The latter values have to come from a model. Current methods of estimation are fragmented and do not scale well. Some assume a specific meter type or don’t work with different building types.

In this competition, you’ll develop accurate models of metered building energy usage in the following areas: chilled water, electric, hot water, and steam meters. The data comes from over 1,000 buildings over a three-year timeframe. With better estimates of these energy-saving investments, large scale investors and financial institutions will be more inclined to invest in this area to enable progress in building efficiencies.

#### A few Challenges faced in the dataset

1. The dataset is huge. (Train: 2.6+ GB, Test: 5.3+ GB)
2. A lot of clustering and grouping because there are too many different buildings segregated into plots.
3. Anamolous Target variable readings in few sectors.
4. Too many outliers. 
