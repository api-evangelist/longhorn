---
title: "V2 Disk Size Aggregation"
url: "https://longhorn.io/blog/20251223-v2-disk-size-aggregation/"
date: "2025-12-23"
author: ""
feed_url: "https://longhorn.io/blog/index.xml"
---
Table of contents Introduction Disk Size Aggregation Overview Why Longhorn Chooses Linux RAID Over SPDK RAID (For Now) SPDK RAID 0 – Capacity Waste SPDK Concat – Capacity Good, Performance Flat Linux Kernel RAID 0 – Best Practical Balance Comparison Table Create an Aggregated Disk Using Linux Kernel RAID Create Aggregated Disk Remove an Aggregated Disk Benchmark Result 1-Replica Volume 3-Replica Volume Conclusion Future Direction Introduction This article is intended for Kubernetes administrators and system engineers running Longhorn v2 on nodes with multiple local disks who want to aggregate…
