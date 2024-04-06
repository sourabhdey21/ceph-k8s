![Ceph Icon](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTDC9M_oGuRQrxzrUc9S0SYs13nRspUXB2XRBOq-VYSgQ&s)

## Ceph Architecture 

### Key Points
- **Persistent Volumes**: Containers running on Kubernetes interact with Ceph storage resources through persistent volumes.
- **Data Replication**: Ceph ensures data replication and distribution across the cluster to prevent data loss.
- **Dynamic Scaling**: Kubernetes dynamically scales the application based on resource demands, leveraging Ceph's scalable storage backend.

### Logical Diagram
![Ceph Architecture ](https://docs.openstack.org/cinder/rocky/_images/ceph-architecture.png)
