# Marketing Mix Modeling

### Business Problem Context

The attached data is **weekly sales data (sales column)** and **marketing data** of TV, Radio and Digital channels in GRPs -Gross Rating Points (tv_grps, radio_grps, digital_grps). And the week's temperature data in the temp column.

The idea is:
- To quantify the effects of different marketing channels on sales
- Calculate the Return on Investment (ROI) of each marketing channel
- Optimize the budget for marketing campaigns.
  

Sales is probably a combination of **a baseline** (which comes from the business, brand, customer loyalty ...), **organic growth** (which can be some %/week), **seasonality* (which might come from temperature variation) and **marketing activities**

You might need to study the concept of **marketing adstock** and how it relates to GRPs: adstock = function of (GRPs, diminishing, decay). 

In this particular case:
- For TV, diminishing can be 120 to 150, decay can be 0.6 to 0.95
- For Radio diminishing can be 150 to 180, decay can be 0.3 to 0.6
- For Digital diminishing can be 70 to 100, decay can be 0.6 to 0.9

### Missions:
- Build predictive model(s) that can predict sales, given the available data
- Estimate **the percentage of sales that is boosted by different marketing channels**

### Expectation:
- Show the ability how to build models, validate models, and tune hyperparameters to select the best model(s)
- Interpret the results with visualization.
