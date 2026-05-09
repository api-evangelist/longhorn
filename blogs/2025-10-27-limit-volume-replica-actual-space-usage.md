---
title: "Limit Volume Replica Actual Space Usage"
url: "https://longhorn.io/blog/20251027-limit-volume-replica-actual-space-usage/"
date: "2025-10-27"
author: ""
feed_url: "https://longhorn.io/blog/index.xml"
---
Table of contents Overview Prerequisite Why a volume replica’s actual space usage can be greater than the spec size How to rely on existing volume settings to limit the space usage Why snapshot deletion and purge will consume extra space Ideal Case If we choose snapshot max count for volume If we choose snapshot max size for volume Limitations More tips for disk space usage efficiency Overview As some users know, a volume replica’s actual space usage can be greater than volume.spec.size.
