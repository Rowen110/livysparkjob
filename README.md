Apache Spark
Apache Livy
Apache NiFi

Scala 2.11 Example Code

Apache NiFi Runner Code

import com.dataflowdeveloper.example.Example
println("Before run")
val job = new Example()
job.run(spark)
println("After run")



