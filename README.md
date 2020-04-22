1. How did changing values on the SparkSession property parameters affect the throughput and latency of the data?

It affected the `inputRowsPerSecond`  and `inputRowsPerSecond`, both through and delay may increased.


2. What were the 2-3 most efficient SparkSession property key/value pairs? Through testing multiple variations on values, how can you tell these were the most optimal?

The most efficient SparkSession properties are: `spark.sql.shuffle.partitions` and `spark.default.parallelism`.

The highest value i observed was `202.8400928279368`.