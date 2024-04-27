
# Predicting Drive Failure

This code goes through 3 different methodologies for predicting drive failures.

## Dataset Features used

<pre>
capacity_bytes = Capacity of the Hard Drive
smart_5_normalized and smart_5_raw = Reallocated Sectors Count 
smart_187_normalized and smart_187_raw = Reported Uncorrectable Errors 
smart_188_normalized and smart_188_raw = Command Timeout 	
smart_197_normalized and smart_197_raw = Current Pending Sectors Count	
smart_198_normalized and smart_198_raw = Offline Uncorrectable Sectors Count	
date_diff = Number of days left till failure
failure = Whether hard drive has failed or not
</pre>

## How to Run

The code can be run by opening the .ipynb file in colab and running it.

For running it locally, the file path will have to be changed accordingly.

## Data

Data has been taken from BackBlaze. We are using data from the year 2016.

https://www.backblaze.com/cloud-storage/resources/hard-drive-test-data

# References

https://www.backblaze.com/blog/using-machine-learning-to-predict-hard-drive-failures/

https://en.wikipedia.org/wiki/Self-Monitoring,_Analysis_and_Reporting_Technology#ATA_S.M.A.R.T._attributes

https://medium.com/geekculture/a-complete-solution-to-the-backbaze-com-kaggle-problem-cf1fab1af529
