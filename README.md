# Ad_Recommendation_Engine

Parameters in the dataset: 

* date : All data are aggregated by date 
* shown : Number of ads shown on a given day. Impressions are free and the companies pay only if a user clicks on the ad 
* clicked (frequency): Number of clicks on the ads
* converted : Number of conversions on the site coming from ads
* avg_cost_per_click : On an average, how much it cost each of those clicks 
* total_revenue : How much revenue came from the conversions 
* ad : Group names (40 groups)


Objective : 

1. Identify 5 best ad groups and justify the metric chosen.

2. Develop a time-series model, for each group, to forecast the number of ads that will be shown on a particular day in the future.

3. Cluster ads groups into 3 clusters:
  a. avg_cost_per_click is going up
  b. avg_cost_per_click is constant
  c. avg_cost_per_click is going down
