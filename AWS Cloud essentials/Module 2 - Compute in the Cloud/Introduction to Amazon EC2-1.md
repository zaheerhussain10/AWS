##### Introduction to Amazon EC2



###### Amazon EC2



Amazon EC2 is more flexible, cost-effective, and faster than managing on-premises servers. It offers on-demand compute capacity that can be quickly launched, scaled, and terminated, with costs based only on active usage.



The flexibility of Amazon EC2 allows for faster development and deployment of applications. You can launch as many or as few virtual servers as needed and configure security, networking, and storage. You can also scale resources up or down based on usage, such as handling high traffic or compute-heavy tasks.







###### Challenges of on-premises resources



Imagine that you're responsible for designing your company's infrastructure to support new websites. With traditional on-premises resources, you must purchase hardware upfront, wait for delivery, and handle installation and configuration. This process is time-consuming, costly, and inflexible because you're locked into a specific capacity that might not align with changing demands.



* Spend money upfront to purchase hardware.
* Wait for the servers to be delivered to you.
* Install the servers in your physical data center.
* Make all the necessary configurations.





###### Benefits of using Cloud Resources



In contrast, with Amazon EC2, you can quickly launch, scale, and stop instances based on your needs without the delays and upfront costs associated with traditional on-premises resources.



* Pay only for the compute time used when an instance is running.
* Provision and launch an Amazon EC2 instance within minutes.
* Scale up or down based on demand.
* Stop using instances after a workload has completed.







##### How Amazon EC2 works







###### Launch an instance



When launching an EC2 instance, you start by selecting an Amazon Machine Image (AMI), which defines the operating system and might include additional software. You also choose an instance type, which determines the underlying hardware resources, such as CPU, memory, and network performance.





###### Connect to the instance



You can connect to an EC2 instance in various ways. Applications can interact with services running on the instance over the network.



Users or administrators can connect using SSH for Linux instances or Remote Desktop Protocol (RDP) for Windows instances. Alternatively, AWS services like AWS Systems Manager offer a secure and simplified method for accessing instances.



###### Use the instance



After you are connected to the instance, you can begin using it to run commands, install software, add storage, organize files, and perform other tasks.











