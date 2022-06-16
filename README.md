# kafka-producer-consumer
Demo shows kafka producer and consumer and event status changes

Kafka steps:
======================================
1. C:\Tools\kafka-3.2>.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties
2. C:\Tools\kafka-3.2>.\bin\windows\kafka-server-start.bat .\config\server.properties
3. C:\training\microservices\kafka\springboot-kafka-producer>java -jar target\springboot-kafka-producer-0.0.1-SNAPSHOT.jar
4. C:\training\microservices\kafka\springboot-kafka-consumer>java -jar target\springboot-kafka-consumer-0.0.1-SNAPSHOT.jar
