##### Directing Traffic with Elastic Load Balancing





###### Elastic Load Balancing



Elastic Load Balancing (ELB) automatically distributes incoming application traffic across multiple resources, such as EC2 instances, to optimize performance and reliability. ***A load balancer serves as the single point of contact for all incoming web traffic to an Auto Scaling group. As the number of EC2 instances fluctuates in response to traffic demands, incoming requests are first directed to the load balancer. From there, the traffic is distributed evenly across the available instances.***



Although ELB and Amazon EC2 Auto Scaling are distinct services, they work in ***tandem(one Behind the other)*** to enhance application performance and ensure high availability. Together, they enable applications running on Amazon EC2 to scale effectively while maintaining consistent performance.





###### ELB benefits:





* **Efficient traffic distribution:**



ELB ***evenly distributes traffic across EC2 instances,*** ***preventing overload on any single instance*** and optimizing resource utilization.





* **Automatic scaling:**



ELB scales with traffic and ***automatically adjusts to changes in demand for a seamless operation*** as backend instances are added or removed.





* **Simplified management:**



***ELB decouples front-end and backend tiers and reduces manual synchronization. It also handles maintenance, updates, and failover to ease operational overhead.***





###### Routing methods



To optimize traffic distribution, These routing strategies ***work together for efficient traffic management and optimal application performance.***





**ELB uses several routing methods:**



* **Round Robin**



Distributes traffic ***evenly across*** all available servers in a ***cyclic manner***.





* **Least Connections**



Routes traffic to the server with the ***fewest active connections***, maintaining a balanced load.





* **IP Hash**



Uses the client’s I***P address to consistently route traffic to the same server***.





* **Least Response Time** 



Directs traffic to the server with the ***fastest response time, minimizing latency***.





