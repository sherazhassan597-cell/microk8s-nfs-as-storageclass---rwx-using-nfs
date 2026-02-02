# microk8s-nfs-as-storageclass---rwx-using-nfs
## Kubernetes NFS RWX StorageClass
This project demonstrate how to configure NFS as a dynamic StorageClass in kubernetes and provision readwritemany volumes
## Tech Stack 
Kubernetes 
NFS Server 
NFS Subdir External Provision 
## Steps Performed
Setup NFS srever 
Install NFS provisioner
Create StorageClass 
Create RWX PVC 
Deploy application using RWX 
Verify shared access across pods 
## Key Concepts 
StorageClass 
Dynamic Provisioning 
RWX Volume PersistentVolumeClaim 
NFS CSI 
# Files Used 
sc-nfs.yaml pvc-nfs.yaml exports commands.txt
## Commands Used
kubectl get po 
kubectl get pv 
kubectl get pvc 
kubectl apply -f sc-nfs.yaml
kubectl apply -f  pvc-nfs.yaml
