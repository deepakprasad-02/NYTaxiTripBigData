# NYTaxiTripBigData
This project emphasises on trying different approaches to optimise MapReduce algorithm


## To execute the program in Hadoop AWS instance, follow the steps

Step 1: Copy the source code provided(BDPAssignment)to hue
Step 2: Copy the source code to master node
Step 3: place ny taxi dat set in hue
Step 4: Run the code 
*	mapreduce - hadoop jar /home/hadoop/BDPAssignment-0.0.1-SNAPSHOT.jar nyc.mapReduce.JobClass /user/s3759108/30_data.csv /user/s3759108/b1
* Combiner - hadoop jar /home/hadoop/BDPAssignment-0.0.1-SNAPSHOT.jar nyc.BDPAssignment.combiner.MainJob /user/s3759108/30_data.csv /user/s3759108/c1
* Partioner - hadoop jar /home/hadoop/BDPAssignment-0.0.1-SNAPSHOT.jar nyc.BDPAssignment.partioner.TripMain /user/s3759108/80_data.csv /user/s3759108/d3
