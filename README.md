


<img width="780" height="516" alt="Screen Shot 2026-04-09 at 8 34 41 PM" src="https://github.com/user-attachments/assets/f9b8fc81-55ec-4b0f-85e7-35c1bccd4ce4" />


## Project Overview

This project demonstrates how machine learning can enhance the monitoring of complex systems, specifically data centers.

### What We're Doing
We generate synthetic data that mimics real-world sensor readings from a data center, including:
- CPU utilization  
- Temperature  
- Network latency  

### Why It Matters
Data centers require continuous, proactive monitoring. Detecting anomalies—unusual patterns in sensor data—is critical because they can indicate:
- Impending hardware failures  
- Overheating  
- Network bottlenecks  
- Security breaches  

Early detection helps:
- Prevent downtime  
- Optimize resource allocation  
- Maintain operational stability  

### How It Works
We leverage NVIDIA RAPIDS AI tools:
- **cuDF** for GPU-accelerated data processing  
- **cuML** for machine learning  

Using **K-Means Clustering**, we:
1. Group similar sensor readings into clusters  
2. Identify data points far from cluster centroids  
3. Flag those points as potential anomalies  

### The Goal
To showcase an automated, scalable approach for detecting critical system deviations—an essential capability for maintaining robust and efficient data center operations.
