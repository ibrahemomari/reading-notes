# Message Queues

A message queue is a form of asynchronous service-to-service communication used in serverless and microservices architectures. Messages are stored on the queue until they are processed and deleted. Each message is processed only once, by a single consumer. Message queues can be used to decouple heavyweight processing, to buffer or batch work, and to smooth spiky workloads.

![](https://stackify.com/wp-content/uploads/2017/01/message-queue-793x397.jpg)

# Review, Research, and Discussion

#### 1. What does it mean that web sockets are bidirectional? Why is this useful?

An important consequence is that you may efficiently push data from the server to the client. Underlying sockets are just kept open (or reopened when needed if they couldn't be kept open).

`WebSockets` allow for a higher amount of efficiency compared to REST because they do not require the HTTP request/response overhead for each message sent and received. When a client wants ongoing updates about the state of the resource, WebSockets are generally a good fit.

#### 2. Does socket.io use HTTP? Why?

yes, to enables interaction between a web browser or other client applications and a web server with lower overhead than half-duplex alternatives such as http polling hence promoting real-time data transfer between the two.

#### 3. What happens when a client emits an event?

The event is passed from the client to the server through websockets

#### 4. What happens when a server emits an event?

The event is passed from the server to the client

#### 5. What happens if a client “misses” an event?

The event is lost

#### 6. How can we mitigate this?

ou can add systems to replay, retry, or resend the event.

---

# Document the following Vocabulary Terms

**Socket**

Software structure within a network node of a computer network that serves as an endpoint for sending and receiving data across the network

**Web Socket**

A WebSocket is a persistent connection between a client and server. WebSockets provide a bidirectional, full-duplex communications channel that operates over HTTP through a single TCP/IP socket connection

**Socket.io**

Socket.IO is a JavaScript library for realtime web applications. It enables realtime, bi-directional communication between web clients and servers.

**Client**

Something making a web request

**Server**
Something sending a web response

**OSI Model**
The OSI Model (Open Systems Interconnection Model) is a conceptual framework used to describe the functions of a networking system. It's made up of seven different abstraction layers: Physical, Data Link, Network, Transport, Session, Presentation, and Application.

**TCP Model**
Concise version of the OSI model. It contains four layers: Process/Application Layer, Host-to-Host/Transport Layer, Internet Layer, Network Access/Link Laye

**TCP**
Transmission Control Protocol. Standard that defines how to establish and maintain a network conversation through which application programs can exchange data

**UDP**
User Datagram Protocol is one of the core members of the Internet protocol suite. With UDP, computer applications can send messages, in this case referred to as datagrams, to other hosts on an Internet Protocol (IP) network

**Packets**
In networking, a packet is a small segment of a larger message. Data sent over computer networks\*, such as the Internet, is divided into packets. These packets are then recombined by the computer or device that receives them.


---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com