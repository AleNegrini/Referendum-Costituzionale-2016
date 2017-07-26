# Referendum Costituzionale 2016
I solved the exercise twice:
  1) with Python (pandas + numpy libraries) 
  2) with Scala + Spark 
  
At the end of each procedure, results obtained have been compared

Solution source code can be found in directories: 
  1) Python -> code_python  
  2) Scala + Spark -> code_scala
  
Output csv files can be found in directory: 
  - output/output_python : csv file produced by python notebooks
    - Data Cleaning.ipynb: notebook for the dataset cleaning
    - Aggregations.ipynb: notebook that computes aggregations on the dataset
    - Data Visualization.ipynb: notebook that visualize results
  - output/output_scala_spark : csv file produced by spark-shell code
  
Initial dataset and intermediate files can be found at: 
  - resources/ScrutiniFI.csv : original dataset
  - resources/ScrutiniFI_cleaned : cleaned dataset
