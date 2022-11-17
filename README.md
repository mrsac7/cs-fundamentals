# Modern CS Fundamentals
> Computer Science Fundamentals Notes

### 1. SSH

Relevant Video: [Beginners Guide to SSH](https://youtu.be/qWKK_PNHnnA)

A secure protocol for logging into someone else's computer. It was desinged as a replacement of Telnet which was not secure. It uses public-key cryptography to authenticate the remote computer and allow it to authenticate user. It is typically used to log into a remote machine and execute commands however it can also be used for transfering files via SSH file transfer (SFTP) or secure copy (SCP).


### 2. SSL (or TLS)

Relevant Video: [What is SSL & TLS?](https:youtu.be/HMoFvRK4HUo)

A secure protocol for communicating across a network without letting someone in between to sniff or eavesdrop on the message exchanged. It protects the data in three ways:

* Confidentiality: Data is only accessible by Client and server [Encryption]
* Integrity: Data is not modified between Client and Server [Hashing]
* Authentication: Client/Server are indeed who they say they are [Public Key Infrastructure]]

### 3. Apache Kafka

Relevant Video: [Apache Kafka in 6 Minutes](https://youtu.be/Ch5VhJzaoaI)

It is like a set of queues that can store and pass messages. There is a distribution strategy to distribute the messages among these queues. It aims to provide high throughput (no. of data packets sent) and low latency (time taken to send a packet) platform.

### 4. Big Data

Relevant Video: [Big Data in 5 Minutes](https://youtu.be/bAyrObl7TYE)

Data coming from a source which produces large volume of data in very less time could be classified as Big Data. Example of such sources are: mobile devices, Healthcare industry, etc. Big Data can be structured, semi-structured or unstructured. Useful insights can be obtained by the processing of Big Data.

### 5. Apache Hadoop

Relevant Video: [Hadoop in 5 Minutes](https://youtu.be/aReuLtY0YMI)

Hadoop provides a framework for:
  1. Distributed storage of Big Data (HDFS)
  1. Processing of Big Data (Map Reduce)
 
### 6. Apache Hive

Relevant Video: [What is Apache Hive?: Understanding Hive](https://youtu.be/cMziv1iYt28)

Hive gives an SQL-like interface (called HiveQL) to perform queries over the data stored in Hadoop's HDFS. These queries convert into Map Reduce Jobs by Hive


