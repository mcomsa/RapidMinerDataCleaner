# RapidMinerDataCleaner

This is a data cleaner project very similar to Randal Olson's DataCleaner in Python but for RapidMiner. 

It is supposed to be used inside RapidMiner to do a first cleaning of data.

# Currently Supported

  * Nominal to Numerical conversion either with Dummy Coding or Unique Integers
  * Replace Missing Values with average/mode or using a model (currently K-NN)
  * Attributes with too many missing values are deleted
  

# Experimental
  * Added a new feature which allows you to parse nominal coloums to numerical. if more than 5% and less than 75% of the nominals are unparsable a new attribute is created containing those unparseable values.
