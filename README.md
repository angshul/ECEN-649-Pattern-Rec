# ECEN-649-Pattern-Rec
Viola Jones Algorithm

There are 5 Jupyter Notebooks (ipython) files. <br/>
AdaBoost-1,3,5-rounds<br/>
AdaBoost-10-rounds<br/>
Threshold<br/>
Cascading<br/>

Make sure python 3.6 is installed. Packages needed to run the files are mentioned in the report.
 Please change the data directory to the absolute path where the dataset folder is located as given below: <br/>

data_dir="C:\\Users\\ANGSHUL\\Downloads\\dataset" <br/>

Note: Extract the dataset folder from the zip/rar file and change the above path in the code to point to the dataset folder. 
I have assumed the zip/rar file has already been extracted and the dataset folder is present, hence there is no code to extract from the compressed folder. <br/>

First run the AdaBoost-1,3,5-rounds file. This file has the code for AdaBoost 1,3 and 5 rounds.
AdaBoost-10-rounds only contains the code for 10 rounds.
Although the same code is used for all cases, the 10 rounds takes much longer to train and hence had to be executed separately on a Google Cloud Console to get the results on time.

The threshold adjusting code is present in the Threshold notebook.
The Cascading bonus has been attempted in the Cascading notebook.

It might take a considerable amount of time to train for 5 and 10 rounds.



