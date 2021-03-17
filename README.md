# Water_Consumption_Forecast
Final Capstone: Project Proposal.


A. Problem. 

In this project we will try to explore what is the best method to forecast the drinking water consumption of the City of New York.
 Although 71% of our planet is covered by water, only a very small proportion is associated with the continental areas to which humans are primarily confined. Over 99% of the water associated with continents is in the form of groundwater or ice and is therefore difficult for humans to use. Humans mostly depend on freshwater streams, rivers, marshes, lakes, and shallow groundwaters; we rely heavily on a rare commodity. Therefore, having the ability to forecast future water consumption would allow governments to manage such vital resources in a sustainable way. 

B. Data. 
	For this project we will use a Kaggle dataset titled “NY Water Consumption In 
The New York City”. The data collection provides a brief history of water    
consumption in the New York City Water Supply System (Based on New York 
City Census population)

This is a dataset hosted by the City of New York. The city has an open data 
platform. 

One possible limitation of the dataset is that the observations are summarized in millions of gallons per day on a yearly average. Averaging on a yearly basis could eliminate some seasonal information that could be useful for model development and prediction.

C. Methodology
We will approach this project as a Time Series , therefore we will try to implement the ARIMA models from the statmodel library. Also we will try to evaluate a Bayesian model included on the Facebook open source library, Prophet.
