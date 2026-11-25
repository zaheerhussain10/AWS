##### Messaging and Queuing





###### EventBridge



— EventBridge is a s***erverless service that helps connect different parts of an application using events***, helping to build scalable, event-driven systems. With EventBridge, you ***route events from sources like custom apps, AWS services, and third-party software to other applications***. ***EventBridge simplifies the process of receiving, filtering, transforming, and delivering events,*** so you can quickly build reliable applications.



EventBridge can route events, like order placed or payment completed, to the relevant services (payment, restaurant, inventory, and delivery). ***It can handle high volumes of events during peak times, making sure each service works independently.*** ***Even if one service fails, EventBridge will store the event and process it as soon as the service is available again.*** EventBridge helps provide a smooth and reliable operation across the entire system.







###### Amazon SQS



— Amazon SQS is a message queuing service that facilitates reliable communication between software components. It can ***send, store, and receive messages at any scale, making sure messages are not lost and that other services don't need to be available for processing.*** In Amazon SQS, an application places messages into a queue, and ***a user or service retrieves the message, processes it, and then removes it from the queue.***





###### **Example:**



A customer support team consists of a support agent and a technical specialist. The support agent is responsible for receiving customer issues, and the technical specialist works on resolving them. This process works well as long as both the agent and specialist are available and coordinated.



However, what happens if the support agent creates a ticket but the technical specialist is busy working on another issue or unavailable? The agent would have to wait until the specialist is free to accept the new ticket, causing delays in resolving customer issues and extending wait times for customers. As the volume of customer issues increases, this process becomes inefficient.



To improve efficiency, they implement a queue system using Amazon SQS. The support agent adds customer issues to the queue, creating a backlog. Even if the specialist is busy, the agent can continue adding new issues. The specialist checks the queue, resolves issues, and updates the agent. This system provides a smooth workflow and helps handle higher volumes without delays or bottlenecks.







###### Amazon SNS



— Amazon SNS is a ***publish-subscribe service*** that publishers use to send messages to subscribers through SNS topics. In Amazon SNS, subscribers can include web servers, email addresses, Lambda functions, and various other endpoints. You will learn about Lambda in more detail later.



**1: Segment the communication**



The company decides to divide the communication into three separate topics, including one for new products, one for special offers, and one for events. Each topic will focus on a specific area of interest.





**2: Let customers choose topics**



Customers can subscribe to the topics they care about, such as the following:

A customer might subscribe only to new product updates.

Another customer might opt only for event notifications.

A third customer might choose to subscribe to new product updates and special offers.





**3: Send tailored notifications**



With Amazon SNS, the company can send personalized notifications to subscribers based on their specific interests. Amazon SNS makes sure that these notifications are promptly delivered to the right audience, improving the efficiency and relevance of the communication.

