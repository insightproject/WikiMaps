# WikiMaps
Trending Topics around the World


I built a data pipeline to easily access and query Wikipedia article traffic data for all available Wikipedia-languages. My data pipeline is based on Lambda-architecture design principles, which allow for high data availability and eventual consistency even in the presence of partitions: 

![alt tag]("images/Screenshot_2014-10-01_00.02.46.png" "Data Pipeline")

I used well-known MapReduce frameworks (Pig/Hive) to clean and process raw Wikipedia traffic data, NoSQL databases (HBase) to enable efficient querying of Wikipedia article traffic, and effective real-time data processors (Kafka/Storm) to handle incoming Wikipedia traffic data streams. 












