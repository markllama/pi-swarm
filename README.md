# Swarm Cluster on Raspberry Pi 5

This repository describes a Docker Swarm cluster deployed on 4 raspberry pi 5b, and provisioned
from a fifth. The cluster is behind a NAT router with two internal interfaces, one for management
and one for data.

The The cluster contains several auxiliary services that are used by the developer application:

* Shared Filesystem: Gluster
* Monitoring
  * Prometheus
  * Cadvisor
* Databases
  * MongoDB
  * PostgreSQL
