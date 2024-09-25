# ABOUT K8s
Kubernetes, often abbreviated as K8s, is an open-source platform for automating the deployment, scaling, and management of containerized applications. But Kubernetes is more than just a container orchestrator. It aims to reduce the burden of orchestrating underlying compute, network, and storage infrastructure, and enable application operators and developers to focus entirely on container-centric workflows for self-service operation.

**Main Function/Usage:**- Kubernetes manages containers, which package an application and its dependencies together to ensure it runs consistently across different environments. Containers are isolated units but lightweight compared to virtual machines.
<br><br>
# NODE
A Node is the fundamental worker machine in a Kubernetes cluster. It can be either a physical machine or a virtual machine in a cloud environment. Each node runs the necessary services to support the containers it hosts, such as the container runtime (e.g., Docker), the Kubelet (which communicates with the Kubernetes control plane), and Kube-proxy (which manages networking for the pods).

**TYPES OF NODES**

*1.Master Node*-The master node is the brain of the Kubernetes cluster and handles scheduling, maintaining the desired state, and managing resources. It contains components like API Server,Scheduler,Controller Manager

*2.Worker Node-* Worker nodes are the machines where application workloads run. These nodes run the containers and host the pods that make up an application. They handle the execution of the actual tasks, networking, and storage management.

# PODS 
A Pod is the smallest and most basic deployable unit in Kubernetes (K8s). It represents a single instance of a running process in your cluster and can contain one or more containers that share the same network and storage resources. Typically, pods are used to run a single container, but there are cases where multiple containers need to work together closely, and in these cases, a pod will contain multiple tightly coupled containers.

# Kubernetes Architecture
A Kubernetes environment consists of a control plane (master), a distributed storage system for keeping the cluster state consistent (etcd), and a number of cluster nodes (Kubelets).
![image](https://github.com/user-attachments/assets/470ef796-7577-4b4f-8842-c8e2a0a13142)
# About Minikube
Minikube is a tool that sets up a Kubernetes environment on a local PC or laptop. This tool provides an easy means of creating a local Kubernetes environment on any Linux, Mac, or Windows system, where you can experiment with and test Kubernetes deployments.
![image](https://github.com/user-attachments/assets/b6b29514-fa38-49fc-9acd-0565b7444012)


**SINGLE NODE CLUSTER**

A single-node cluster in Kubernetes refers to a cluster where both the control plane (which manages the cluster) and the worker node (which runs applications) are on the same machine. It runs all the components of Kubernetes, including the API server, scheduler, and Kubelet, but on just one physical or virtual node.
<br>
# How to install Minikube with Ubuntu
1.**STEP 1:** Connect to the Server via PuTTY

Open PuTTY
<br>
Enter the Hostname or IP Address
<br>
Click Open
<br>
Login to the server by writing ubuntu
<br>
<br>
2.**STEP 2:** Install docker using the following command
<br>
curl -sL https://github.com/ShubhamTatvamasi/docker-install/raw/master/docker-install.sh | bash















