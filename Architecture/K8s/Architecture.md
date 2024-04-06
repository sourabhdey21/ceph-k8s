<img src="https://kubernetes.io/images/kubernetes-horizontal-color.png" width="500" height="200">

## Kubernetes Architecture

### Key Points
- **Pods**: The smallest deployable units in Kubernetes, which can contain one or more containers.
- **Services**: An abstraction that defines a logical set of Pods and a policy by which to access them.
- **ReplicaSets**: Ensures that a specified number of pod replicas are running at any given time.
- **Deployments**: Provides declarative updates to Pods and ReplicaSets.
- **Namespaces**: Provides a scope for Names to avoid naming collisions.
- **Nodes**: A worker machine in Kubernetes, which may be a VM or physical machine, depending on the cluster.
- **Master**: A node that controls the cluster.
- **Kubelet**: An agent that runs on each node in the cluster. It makes sure that containers are running in a Pod.
- **KubeProxy**: Maintains network rules on nodes.
- **KubeScheduler**: Assigns a node to newly created Pods.
- **KubeControllerManager**: Runs controller processes.
- **Cloud Controller Manager**: Runs controllers that interact with the underlying cloud providers.

### Benefits of Using Ceph as Backend Storage for Kubernetes

1. **Scalability**: Ceph allows for seamless scaling of storage resources to meet changing demands in Kubernetes environments.
   
2. **Reliability**: Ensures data redundancy and fault tolerance through Ceph's distributed storage system, enhancing data reliability for containerized applications.
   
3. **Integration**: Facilitates smooth communication and data storage operations between Ceph and Kubernetes through an integration layer.
   
4. **Dynamic Resource Allocation**: Enables Kubernetes to dynamically scale applications based on resource requirements, leveraging Ceph's scalable storage backend.
   
5. **High Availability**: Ceph enhances availability by distributing data across multiple nodes in a cluster, reducing the risk of data loss.

### Workflow
1. Containers running on Kubernetes interact with Ceph storage resources through persistent volumes.
2. Ceph ensures data replication and distribution across the cluster to prevent data loss.
3. Kubernetes dynamically scales the application based on resource demands, leveraging Ceph's scalable storage backend.

### High-Level Design Diagram
![Kubernetes Architecture](https://www.opsramp.com/wp-content/uploads/2022/07/Kubernetes-Architecture-1536x972.png)

