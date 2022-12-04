# Distributed-Video-Streaming-with-Python-and-Kafka
Distributed Video Streaming with Python and Kafka

https://medium.com/@kevin.michael.horan/distributed-video-streaming-with-python-and-kafka-551de69fe1dd

**Start kafka**
```
cd c:/kafka
bin\windows\zookeeper-server-start.bat config/zookeeper.properties
```

```
cd c:/kafka
bin\windows\kafka-server-start.bat config/server.properties
```

**Start the consumer**
```
python consumer.py
```

**Start the producer**
```
python producer.py my_awesome_video.mp4
```
