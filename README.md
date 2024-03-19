# kafka

How do you hanlde duplicate msg in kafka with respect to consumer: consumer-group

Apache kafka: default msg size of kafka? -> 1MB per message in the topic

Apache Kafka: sendng msg of 15mb from producer to broker and from broker to consumer, what all are the changes, parameter you would be configuering?

In apache Kafka, above 50mb how will you send? -> Exception encounter

what is replication factor in kafka? -> No of copies of data over multiple broker

why we need replication factor or use of replication factor

what is fault tolerance? is it possible to implement fault tolerance using replication factor?

What is Event Driven Architecture? Kafka-> pub-sub-broker

How Event Driven Architectture works and what it's advantage?

Which kafka connector you have used in you project?

What is the difference between Kafka and Kafka Connect?

What is event driven model - Kafka

What is Dead-letter Queue-> secondary Kafka topic that receives the messages which the Kafka Consumer failed to process

How to handle Duplicate msg in Kafka wrt consumer -> consumer Group,  implement an idempotentmessage handler, tracking all received messages and discard duplicate ones

How to implement idempotent message handler in Kafka?

How to Maintain the Order of Messages in Kafka Topics?

How to manage Offset in Kafka

How to Tune Producer Performance

How to Tune Performance of Kafka Consumer?

Assign and Seek in Kafka Consumer

What id ACK and ISR in Kafka Producer

Retry and inflight connection to maintain order in Kafka

Can a Kafka message be consumed twice?

How do I prevent duplicates in Kafka topic?

How to connect Kafka with ELK stack?

What more we will get from Kafka over any other MQ & limitation

Explain Consumer group concept in kafka

In one Consumer group there two consumers, if there is any update(msg) happened, will all consumer get the same message?

In kafka topic, 1 message and two consumers are running from different consumer group, now who will read the message or all will? -> All

Why do we need to have separate consumer group?

One MS sharing a msg to another MS via Kafka, how do you confirm that particular msg is read.

