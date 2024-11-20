# Hadoop-Hive-Spark cluster + Jupyter on Docker

## Software

* [Hadoop 3.3.6](https://hadoop.apache.org/)

* [Hive 4.0.0](http://hive.apache.org/)

* [Spark 3.4.4](https://spark.apache.org/)

## Quick Start

To deploy the cluster, run:
```
make
docker-compose up
```

## Access interfaces with the following URL

### Hadoop

ResourceManager: http://localhost:8088
https://i.imgur.com/CG8aFAP.png
NameNode: http://localhost:9870
https://i.imgur.com/wfcyTv5.png
HistoryServer: http://localhost:19888
https://i.imgur.com/I7aSt5u.png
Datanode1: http://localhost:9864
Datanode2: http://localhost:9865
https://i.imgur.com/V2wlQ3k.png
NodeManager1: http://localhost:8042
NodeManager2: http://localhost:8043
https://i.imgur.com/mCBfxW6.png
### Spark
master: http://localhost:8080
https://i.imgur.com/x53R0Ov.png
worker1: http://localhost:8081
worker2: http://localhost:8082
https://i.imgur.com/tyLfR1E.png
history: http://localhost:18080
https://i.imgur.com/QXeHuCe.png
### Hive
URI: jdbc:hive2://localhost:10000

### Jupyter Notebook
URL: http://localhost:8888
https://i.imgur.com/S8OnTAU.png
example: [jupyter/notebook/pyspark.ipynb](jupyter/notebook/pyspark.ipynb)
