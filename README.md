# CITS5503_SparkAnalysis
## Analysis of discussion board messages with Apache Spark.

<img src="Selection_033.png" width="1000"> <img src="Selection_034.png" width="1000">

This project involed using Apache Spark to analyize the statistics of the 4chan/mu Music board to provide 
information about regurally discussed topics and peek discussion times. Apache Spark was used as a high perfomance batch processing tool to efficently extract discussion data. The following instructions shows how to use the program developed.

## 1. Access Jupyter Server
The program is currently being run on a jupyter notebook server on a AWS ec2 machine.
Access it [Here](http://ec2-35-161-247-49.us-west-2.compute.amazonaws.com:8888/notebooks/Board_Analysis.ipynb).

## 2. Run and Enjoy Live Statistical Analysis Results
Run the first cell and view the live statistics being plotted in the output.
Change **x_time** to vary the time interval (in seconds) between data processing.
