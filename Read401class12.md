Socket.IO
===
 
Socket.IO enables real-time, bidirectional and event-based communication.
It works on every platform, browser or device, focusing equally on reliability and speed.

**Real-time analytics**
Push data to clients that gets represented as real-time counters, charts or logs.

**Instant messaging and chat**
Socket.IO's "Hello world" is a chat app in just a few lines of code

**Binary streaming**
Starting in 1.0, it's possible to send any blob back and forth: image, audio, video.

**Document collaboration**
Allow users to concurrently edit a document and see each other's changes.


---

Review, Research, and Discussion
===

#### 1. What is the benefit of transforming data into packets?
The main purpose of networking is to share data between computers. A file has to be broken up into small chunks of data known as data packets in order to be transmitted over a network. The data is then re-built once it reaches the destination computer. Networking hardware is required to connect computers and manage how data packets are communicated. Protocols are used to control how data is transmitted across networks.

#### 2. UDP is often referred to as a connectionless protocol. Why is this?
UDP is a connectionless protocol.
 in contrast, allow data to be exchanged without setting up a link between processes. Each unit of data, with all the necessary information to route it to the intended destination, is transferred independent of other data packets and can travel over different paths to reach the final destination. Some data packets might be lost in transmission or might arrive out of sequence to other data packets.

 `Examples` of applications that use connectionless transport services are broadcasting and tftp. Early implementations of NFS used UDP, whereas newer implementations prefer to use TCP.

 #### 3. Can a socket server application have multiple socket connections?

Yes, Multiple listening TCP sockets, all bound to the same port, can co-exist, provided they are all bound to different local IP addresses. Clients can connect to whichever one they need to.

#### 4. Can a socket connection application be connected to multiple socket servers?

For a `stateless protocol (ie UDP)`, there is no problem because "connections" don't exist - multiple people can send packets to the same port, and their packets will arrive in whatever sequence. Nobody is ever in the "connected" state.

For a `stateful protocol (like TCP)`, a connection is identified by a 4-tuple consisting of source and destination ports and source and destination IP addresses. So, if two different machines connect to the same port on a third machine, there are two distinct connections because the source IPs differ. If the same machine (or two behind NAT or otherwise sharing the same IP address) connects twice to a single remote end, the connections are differentiated by source port (which is generally a random high-numbered port)

#### 5. Can an application be both a socket server and a socket connection?
either Yes or No,
Most applications that use both a client and server socket will be multithreaded. The reason for this is simply because the server needs to listen continuously to the port that it is connected to. In the meantime, the rest of the application will need to continue, sending messages through the client socket and doing whatever else needs to be done. Often, the client socket would also run in its own thread so sending data over it won't block the execution of the main application.
The main difference between a client and server is that the server is continuously waiting for a client to connect so data can be exchanged by both. The client is generally just making quick connections and will close again so the client port can be used for another task.


---

Document the following Vocabulary Terms
===

***Observer Pattern***
is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.

***Listener***
s a method which is called when the user does something (eg, click a button) that the programmer has indicated they want to be notified of. The listener method is passed an event parameter that may tell something about what happeened.

***Event Handler***
 are signals fired inside the browser window that notify of changes in the browser or operating system environment. Programmers can create event handler code that will run when an event fires, allowing web pages to respond appropriately to change.

***Event Driven Programming***
 is designed to detect events as they occur, and then deal with them using some event-handling procedure

***Event Loop***
 is the secret by which JavaScript gives us an illusion of being multithreaded even though it is single-threaded.
 Here the callback function in the event queue has not yet run and is waiting for its time into the stack when the SetTimeOut() is being executed and the Web API is making the mentioned wait.

***Event Queue***
is a repository where events from an application are held prior to being processed by a receiving program or system.

***Call Stack***
 a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function

***Emit/Raise/Trigger***
`emit`:is to trigger named event(s) which in turn cause functions called listeners to be called.

`Raise`:Execution of the current function will stop (the statements after throw won't be executed), and control will be passed to the first catch block in the call stack. If no catch block exists among caller functions, the program will terminate.

`Trigger`:method triggers the specified event and the default behavior of an event (like form submission) for the selected elements.
***Subscribe***
create an Observable instance that defines a subscriber function. ... To execute the observable you have created and begin receiving notifications, you call its subscribe() method, passing an observer. This is a JavaScript object that defines the handlers for the notifications you receive.

***database***
 is an organized collection of structured information, or data, typically stored electronically in a computer system. 

 
---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com
