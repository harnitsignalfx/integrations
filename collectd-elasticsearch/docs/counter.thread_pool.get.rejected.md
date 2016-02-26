---
title: Rejected Get Requests
brief: Number of rejected get requests
metric_type: counter
---
### Rejected Get Requests

> The number of get requests that have been rejected on this node since it started.

If the get request queue fills up to its limit, new work units will begin to be rejected, and you will see that reflected in this rejected metric. This is often a sign that your cluster is starting to bottleneck on some resources, since a full queue means your node/cluster is processing at maximum speed but unable to keep up with the influx of work.