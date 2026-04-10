


<img width="780" height="516" alt="Screen Shot 2026-04-09 at 8 34 41 PM" src="https://github.com/user-attachments/assets/f9b8fc81-55ec-4b0f-85e7-35c1bccd4ce4" />


Project Overview
This project demonstrates how machine learning can enhance the monitoring of complex systems, specifically data centers.

What we're doing: We're creating synthetic data that mimics sensor readings from a data center (e.g., CPU utilization, temperature, network latency).

Why it's crucial for data centers: Data centers require continuous, proactive monitoring. Identifying anomalies – unusual patterns in sensor data – is vital. These anomalies can signal critical issues like impending hardware failures, overheating, network bottlenecks, or security breaches. Early detection prevents downtime, optimizes resource allocation, and ensures operational stability.

How we're doing it: We leverage NVIDIA's RAPIDS AI tools (cuML and cuDF) for GPU-accelerated analysis. Using K-Means Clustering, we group similar sensor readings. Readings significantly distant from any cluster centroid are flagged as potential anomalies.

The Goal: To showcase an automated approach to detecting critical system deviations, a skill invaluable for maintaining robust and efficient data center operations.
