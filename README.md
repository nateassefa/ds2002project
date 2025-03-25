# DS2002Project

by Nate Assefa and Tsion Abate

To run the ETL pipeline, you must download the players.csv file also included and upload it in the local file storage on Colab. Upon loading the players.csv into colab, you can then run the file and you will be able to ingest the player.csv locally and then there is access credientials included to access the other dataset via Kaggle API. 

After running this, you will have ingested both datasets for this ETL pipeline. At some point, you will have the option to convert both the dataset retreived through the Kaggle API (transfers.csv) and the local machine (players.csv). You will be asked to input the file extension you would like to convert both datasets to (JSON, SQL, Excel, etc). 

After doing so, the conversion will be compelete. There will then be a few columns added and removed. Next, there will be some data analysis and visualization to perform some simple data analysis and then visualize it. 

Then, the transformed data will be stored in a SQLite database. Finally, there will be some data summaries to show records, columns, and some other information before and after the pipeline. 
