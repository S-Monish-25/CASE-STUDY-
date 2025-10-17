# CASE-STUDY-

Case Study Title: Resource Allocation and Cost Optimization in an OpenStack Private Cloud

Case Overview:

ABC Cloud Services runs a private cloud using OpenStack to host virtual machines (VMs) for internal development, testing, and production workloads. Their cloud infrastructure comprises:

5 Compute Nodes, each with:
64 vCPUs
256 GB RAM
2 TB SSD storage
OpenStack Services Deployed:
Nova (Compute)
Neutron (Networking)
Cinder (Block Storage)
Glance (Image Management)
Keystone (Identity)
Horizon (Dashboard)
Heat (Orchestration)

They are considering expanding their cloud but want to first evaluate current capacity usage, VM density, and cost efficiency. The goal is to calculate whether their resource usage aligns with business needs and how to optimize it.

Case Study Questions – OpenStack Calculation in Cloud Computing

1. Resource Utilization:

Based on the current infrastructure, what is the total available compute capacity in terms of:
Total vCPUs
Total RAM
Total storage

2.Storage Allocation:

Given 10 TB of total block storage across the cloud, how many VMs can be supported if:
a) Each VM is allocated 100 GB block storage
b) Snapshot storage consumes 20% extra on average

**SOLUTIONS:**

Cloud Computing Efficiency Case Study
Problem 1: Encryption Time Calculation

Scenario:
A company uses AES-256 encryption to secure its data before uploading it to the cloud. It takes 0.05 seconds to encrypt 1 MB of data.

Question:
How long will it take to encrypt 2 TB of data before upload?

Solution:
1 TB = 1024 GB = 1,048,576 MB
2 TB = 2 × 1,048,576 MB = 2,097,152 MB

Time to encrypt 1 MB = 0.05 seconds
Time to encrypt 2 TB = 2,097,152 × 0.05 = 104,857.6 seconds

Converting to hours:
104,857.6 ÷ 3600 ≈ 29.13 hours

Answer: It will take approximately 29.13 hours to encrypt 2 TB of data.

Problem 2: CPU Utilization Efficiency

Scenario:
A VM is allocated 8 vCPUs, but only uses 5.5 vCPUs on average.

Question:
What is the CPU utilization efficiency?

Solution:
CPU utilization efficiency = (Average CPU used ÷ Total CPU allocated) × 100

= (5.5 ÷ 8) × 100
= 68.75%

Answer: The CPU utilization efficiency is 68.75%.

Problem 3: Network Throughput Efficiency

Scenario:
A cloud server has a maximum bandwidth of 1 Gbps, but during peak hours it only uses 600 Mbps.

Question:
What is the network throughput efficiency?

Solution:
Network throughput efficiency = (Actual throughput ÷ Maximum throughput) × 100

= (600 ÷ 1000) × 100
= 60%

Answer: The network throughput efficiency is 60%.

Problem 4: Energy Efficiency

Scenario:
Two cloud setups process the same workload:

Setup A: 500W for 2 hours

Setup B: 300W for 3.5 hours

Question:
Which setup is more energy-efficient?

Solution:
Energy consumed = Power × Time

Setup A: 500 × 2 = 1000 Wh

Setup B: 300 × 3.5 = 1050 Wh

Even though Setup B consumes slightly more energy (1050 Wh vs 1000 Wh), we also consider efficiency per workload. Assuming the workload is the same, Setup A is slightly more energy-efficient.

Answer: Setup A is more energy-efficient.

Problem 5: CPU Utilization for VMs

Scenario:
A physical server has 16 cores and each VM uses 2 cores. CPU utilization is optimal at 75%.

Question:
What is the maximum number of VMs that can be efficiently hosted?

Solution:
Maximum usable cores = Total cores × Optimal utilization
= 16 × 0.75 = 12 cores

Each VM uses 2 cores:
Maximum VMs = 12 ÷ 2 = 6 VMs

Answer: Maximum 6 VMs can be efficiently hosted.
