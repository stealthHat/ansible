# Small ansible playbook for my cluster.

  Im running this k8s cluster on a raspberry pi using ubuntu server [arm64](https://ubuntu.com/download/server/arm)

## Roles
 - host-setup: Makes the basic configuration of the system
 - containerd: install containerd as the container runtime of k8s 
 - nodes: Makes the changes needed to run k8s on ubuntu arm64
 - master: Install de k8s service and configure the control plane
 - worker: Adds nodes to the control plane 
