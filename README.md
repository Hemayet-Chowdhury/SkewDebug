# SkewDebug
A tool to detect source code location of skews in Spark PipeLines
Tool is created as a class file in src/main/scala/SkewDetection/




How to use :

Step 1 : import class.

Step 2 : create a SkewDebug object.

Step 3 : pass your spark context as a constructor to the SkewDebug class during object creation.

Step 4 : call the printlog function from the SkewDebug object.

Step 5 : run your pipeline.

Example pipeline and tool usage in src/main/scala/hc/PipeLine

The dataset location may need to be changed. We are adding the ticket_flights.csv data we used in this github repo in the data folder.
