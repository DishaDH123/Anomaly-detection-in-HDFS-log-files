# Anomaly-detection-in-HDFS-log-files

- This project uses Random forest algorithm to predict if an HDFS log is an anomaly or not. 
- The log was parsed using Microsoft excel
- The parsed log was further manipulated using python to extract the required fields.
- The log message was parsed such that the count of each word in the log message was captured. 
- The words were chosen based on the criticality of the word to be an anomaly message. ( Example- Blocked, info, terminate etc)
- The weights of each of the words occuring was calculated based on the total number of words in each log message.
- Feature importance was performed to include only the required fields.
- A test accuracy of 97.2% was obtained before feature importance.
- The test accuracy was 97.3% after the feature importance technique was adapted.
