Event Driven Architecture
===


is a software architecture paradigm promoting the production, detection, consumption of, and reaction to events.

An event can be defined as "a significant change in state". For example, when a consumer purchases a car, the car's state changes from "for sale" to "sold". A car dealer's system architecture may treat this state change as an event whose occurrence can be made known to other applications within the architecture. From a formal perspective, what is produced, published, propagated, detected or consumed is a (typically asynchronous) message called the event notification, and not the event itself, which is the state change that triggered the message emission. Events do not travel, they just occur. However, the term event is often used metonymically to denote the notification message itself, which may lead to some confusion. This is due to Event-Driven architectures often being designed atop message-driven architectures, where such communication pattern requires one of the inputs to be text-only, the message, to differentiate how each communication should be handled.


---

##### 1. What’s the difference between a FIFO and a standard queue?
*`Standard Queue`*
* Support a nearly unlimited number of transactions per second (TPS) per API action.
* Support “At-Least-Once” message delivery but occasionally more than one copy of a message might be delivered.
* Support best effort basis ordering of messages.
* Distributed in nature, stores copies of your messages on multiple servers for redundancy and high availability.
* Does not support grouping of messages.
* Does not support content-based deduplication.
* Used when throughput is more important than ordering.

*`FIFO Queue`*
* Support high number (3,000 msg/ps with batching and 300 msg/ps without batching) of transactions per second (TPS) per API action.
* Support “Exactly-Once” message processing in which a message is delivered once and remains available until a consumer processes and deletes it.
* Support “First-In-First-Out” delivery where the order in which messages are sent and received is strictly preserved.
* Not distributed in nature.
* Support grouping of messages.
* Support content-based deduplication.
* FIFO queue name must end with the .fifo suffix.
* Used when ordering is more important than throughput.

##### 2. How can the server be assured a message was properly received?
You could set up your client to send back a response when it recieves a message.

##### 3. What classic design pattern is best represented by event driven programming?

The observer pattern 

##### 4. How do you test an event driven system?
Integrate logging into the event system and then write unit tests utilizing the spy method.

---

Document the following Vocabulary Terms
===

**FIFO Queue**

queues are designed to enhance messaging between applications when the order of operations and events is critical, or where duplicates can't be tolerated.

**Pub/Sub**

`Pub/Sub` allows services to communicate asynchronously, with latencies on the order of 100 milliseconds.

`Pub/Sub` is used for streaming analytics and data integration pipelines to ingest and distribute data. It is equally effective as messaging-oriented middleware for service integration or as a queue to parallelize tasks.

`Pub/Sub` enables you to create systems of event producers and consumers, called publishers and subscribers. Publishers communicate with subscribers asynchronously by broadcasting events, rather than by synchronous remote procedure calls (RPCs).


---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com