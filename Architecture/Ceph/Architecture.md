<img src="https://www.vectorlogo.zone/logos/ceph/ceph-icon.svg" width="100" height="100">


## Ceph Architecture 
Ceph - a scalable distributed storage system

### Key Points
- **Persistent Volumes**: Containers running on Kubernetes interact with Ceph storage resources through persistent volumes.
- **Data Replication**: Ceph ensures data replication and distribution across the cluster to prevent data loss.
- **Dynamic Scaling**: Kubernetes dynamically scales the application based on resource demands, leveraging Ceph's scalable storage backend.

### Logical Diagram
![Ceph Architecture ](https://docs.openstack.org/cinder/rocky/_images/ceph-architecture.png)


### Features provided by Ceph to Kubernetes Deployment
- **Scalability**: Ceph allows for seamless scaling of storage resources to meet changing demands in Kubernetes environments.
- **Reliability**: Ensures data redundancy and fault tolerance through Ceph's distributed storage system, enhancing data reliability for containerized applications.
- **Integration**: Facilitates smooth communication and data storage operations between Ceph and Kubernetes through an integration layer.
- **Dynamic Resource Allocation**: Enables Kubernetes to dynamically scale applications based on resource requirements, leveraging Ceph's scalable storage backend.
- **High Availability**: Ceph enhances availability by distributing data across multiple nodes in a cluster, reducing the risk of data loss.

### Technical Points
- **RADOS**: Ceph's Reliable Autonomic Distributed Object Store is the primary storage system for Ceph. It provides a scalable and reliable storage solution for Kubernetes.
- **CRUSH**: Ceph's Controlled Replication Under Scalable Hashing algorithm ensures data is distributed across the cluster in a balanced and efficient manner.
- **RBD**: Ceph's Rados Block Device provides block storage for Kubernetes. It is integrated with Kubernetes through the Rook project.
- **CephFS**: Ceph's File System provides file storage for Kubernetes. It is also integrated with Kubernetes through the Rook project.
- **RGW**: Ceph's Rados Gateway provides object storage for Kubernetes. It is integrated with Kubernetes through the Rook project.

