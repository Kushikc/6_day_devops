DAY 2
Scaling Types in Cloud Infrastructure
🔹 Horizontal Scaling (Scaling Out/In)
•	What it is: Adding more machines/instances to handle increased traffic.
•	Example: If one server can't handle 1 million users, you add more servers (like 2, 3, 4…) to balance the load.
•	Used when: You need high availability and scalability.
•	Cloud Benefit: Easy to do using services like AWS EC2 + Auto Scaling + Load Balancer.
🔹 Vertical Scaling (Scaling Up/Down)
•	What it is: Increasing the resources (CPU, RAM, Storage) of a single server.
•	Example: Upgrading a t2.medium EC2 instance to a t2.large (more CPU/RAM).
•	Used when: You want more power in one machine without changing architecture.
•	Limitation: There's always a hardware limit to how much you can scale up.

1.load balancer : to distribute the incoming application traffic to registered  targets called servers.
2. autoscaling - automatically add or remove servers based on traffic and defined policy
3. cloud and watch alarms : will trigger the alarms when there is a problem in servers , whenever crossed the CPU UTILIZATION THRESHOLD
4. sns - simple notification service ----> sends notification to the registerd emails

