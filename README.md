# WikiMaps
TRENDING TOPICS AROUND THE WORLD


I built a data pipeline to easily access and query Wikipedia article traffic data. My API delivers page views, page rank, and popularity index of any Wikipedia topic, for any language in which the topic exists.   

My data pipeline adopts Lambda-architecture design principles, allowing for high data availability and eventual consistency even in the presence of partitions: 

![alt tag](images/Data_Pipeline1.png "Data Pipeline")

I use conventional MapReduce frameworks (Pig, Hive) to clean and process raw Wikipedia traffic data. I use NoSQL databases (HBase) to efficently serve processed Wikipedia data. I add real-time components (Kafka/Storm) to handle incoming Wikipedia traffic streams, ensuring high data availability.




























