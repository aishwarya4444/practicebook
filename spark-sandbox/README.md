# spark-scala-sandbox
Sandbox for playing with Spark and Scala 

## Commands for building the project

### Building Jar

    sbt package

### Executing Code    
    $SPARK_HOME/bin/spark-submit --class="CountWords" --master local[4] target/scala-2.10/spark-sandbox-project_2.10-1.0.jar
    $SPARK_HOME/spark-submit --class="CountValues" --master local[4] target/scala-2.10/spark-sandbox-project_2.10-1.0.jar
 
## References
- http://spark.apache.org/docs/latest/quick-start.html
