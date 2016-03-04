 # Spark Tutorial
  https://github.com/databricks/learning-spark
 
 
 # Run examples
 ./spark-submit \
--class org.example.sparktutorial.mini.SparkWordCount \
--master spark://xxxx:7077  \
--num-executors 2 \
/xxxx/SparkTutorial-0.0.1-SNAPSHOT.jar \
/xxxx/spark-1.6.0-bin-hadoop2.6/README.md