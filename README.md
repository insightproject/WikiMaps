# WikiMaps
TRENDING TOPICS AROUND THE WORLD


I built a data pipeline to easily access and query Wikipedia article traffic data. My API delivers page views, page rank, and popularity index of any Wikipedia topic, for any language in which the topic exists. 

My data pipeline follows well-known Lambda-architecture design principles, allowing for high data availability and eventual consistency even in the presence of partitions: 

![alt tag](images/Data_Pipeline.png "Data Pipeline")

I use standard MapReduce frameworks (Pig/Hive) to clean and process raw Wikipedia traffic data. I use NoSQL tables (HBase) to enable efficient querying of the aggregated Wikipedia data. I add a real-time pipeline (Kafka/Storm) to handle any incoming Wikipedia traffic data streams, thus insuring that my API is always up to date.



















