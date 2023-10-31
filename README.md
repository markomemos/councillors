# Using Municipal Open Data to Analyze Councillor Voting Patterns

This repository has two notebooks, both of which analyze the behaviour of city councillors.

The `councillor_attendance.ipynb` notebook examines the Toronto city council's attendance data going back to 2006. This is a fairly straight-forward exploratory analysis of the data, highlighting how to clean the data and ultimately analyzing which councillors attended their meetings and which did not.

The `councillor_clustering.ipynb` notebook examines councillor voting behaviour and attempts to group the councillors, even across multiple terms, based on their voting similarities. The data cleanup and transformation is explained, but the emphasis lies in the development of a custom clustering algorithm, which is described in-depth. The process was developed using Toronto council data, then tested on Calgary council data. Network graphs are also created relating councils for each term and city.
