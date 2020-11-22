# SF-Crime-Statistics

### How did changing values on the SparkSession property parameters affect the throughput and latency of the data?
Depending on the values the troughput can be increased or decreased.

### What were the 2-3 most efficient SparkSession property key/value pairs? Through testing multiple variations on values, how can you tell these were the most optimal?
I wanted to increase the value ```processedRowsPerSecond```. This was possible by changing the value ```maxOffsetsPerTrigger ```.
