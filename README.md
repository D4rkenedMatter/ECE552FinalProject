# ECE552FinalProject - Zachary Wade and Zachary Warner

This Code Respoitory was written for the GMU ECE552 BigData Class in Spring 2023

# How To Use
1. Place the entire repository folder within your jupyter notebook enviornment.
2. If you do not already have the parquet data, download this dataset (https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents) and run the "RawDataCleaner.ipynb" notebook
3. If your enviornment does not have geopandas installed run the "DownloadGeoPandas.ipynb" notebook and verify geopandas was installed correctly
4. Spark must be installed in your jupyter enviornment. This will not be included in the instructions.
5. A MongoDB instance must also be running, which will not be included in the instructions.
6. After the above has been done, check the "ImportsConstantsSparkInit.ipynb" notebook and adjust the URI for your MongoDB server, as well as the amount of memory you desire to dedicate to Spark. The default is 8g. If you do not give enough, the code may timeout and require you to make other changes to timeout timers and such for Spark.
7. Go to the "MainRunFile.ipynb" notebook and run it. All dataaggregation and plotting will be done.
8. If adjusting to any of the plots or data aggregation is desired, you can go to the relevant folders and change the code to any of the necessary files as desired. These files can also be run independantly (Plotting code requires the relevant data aggregation to have been run and populated in MongoDB first)
