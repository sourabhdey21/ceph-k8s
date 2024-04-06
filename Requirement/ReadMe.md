## Hardware Requirements for Kubernetes and Ceph Deployment in Production Workload

### Kubernetes
| Node Type | CPU Cores | RAM | OS Disk | Network Bandwidth |
|-----------|-----------|-----|---------|-------------------|
| Master    | 8         | 16GB| 100GB   | 10Gbps             |
| Worker    | 8         | 16GB | 100GB  | 10Gbps             |
| Worker    | 8         | 16GB | 100GB  | 10Gbps             |

### Ceph
| Node Type | CPU Cores | RAM | OSD Disk | OSD Daemon Disk | Network Bandwidth |
|-----------|-----------|-----|----------|-----------------|-------------------|
| Monitor   | 8         | 16GB| -        | -               | 10Gbps            |
| Monitor   | 8         | 16GB| -        | -               | 10Gbps            |
| Monitor   | 8         | 16GB| -        | -               | 10Gbps            |
| OSD       | 8         | 16GB|250GB     | 250GB    (Demo) | 10Gbps            |
| OSD       | 8         | 16GB|250GB     | 250GB    (DEMO) | 10Gbps            |
| OSD       | 8         | 16GB|250GB     | 250GB    (DEMO) | 10Gbps            |
| MGR       | 8         | 16GB| -        | -               | 10Gbps            |
| MGR       | 8         | 16GB| -        | -               | 10Gbps            |
| MGR       | 8         | 16GB| -        | -               | 10Gbps            |
| RGW       | 8         | 16GB| -        | -               | 10Gbps            |
| RGW       | 8         | 16GB| -        | -               | 10Gbps            |
| RGW       | 8         | 16GB| -        | -               | 10Gbps            |

### Important 
Basically for POC Setup Requirement is three servers one master and 2 workers . One three server we wil going to install kubernetes as well as ceph storage cluster both.








