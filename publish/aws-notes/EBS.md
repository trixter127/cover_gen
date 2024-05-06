---
title: Ebs
---

# Elastic Block Storage 
---

To attach an [[EC2]] Server as storage and boot volumes

### Types :
- General Purpose SSD (gp3)
- General Purpose SSD (gp2)
- Provisioned IOPS SSD (io1)
- Provisioned IOPS SSD (io2)
- Cold HDD (sc1)
- Throughput Optimized HDD (st1)
- Magnetic (standard)

| Type              | IOPS/Data    | IOPS/Throughput per Volume | Durability | Use Case                                             |
| ----------------- | ------------ | -------------------------- | ---------- | ---------------------------------------------------- |
| **GP2** , **GP3** |     3 IOPS/GiB         | 16000 IOPS                 | 99.9%       | Boot Disks, General Apps                             |
| **IO1**           | 50 IOPS/GiB  | 64000  IOPS                | 99.9%      | OLTP , Latency sensitive                             |
| **IO2**           | 500 IOPS/GiB | 64000  IOPS                | 99.999%     | OLTP , Latency sensitive                             |
| **ST1**           | -            | 500MB/s Throughput         | 99.9%       | Big Data, Data Warehouse, ETL, Cant be a boot Volume |
| **SC1**           | -            |   250 MB/s Throughput                         |    99.9%        |  less frequently accessed data, Cant be a boot Volume, LOWEST COST                                                    |

***
### Snapshots 

- Point in Time Copy of the EBS Volume
- Encrypted Snapshots -> Encrypted EBS Volumes 
- Unencrypted Snapshots -> Unencrypted Volumes 
*** 
