*** What is a vcluster ***
A vcluster is a virtaul cluster, that uses the underlying kubernetes cluster to make a "cluster".

The vcluster is created in a namespace, and that name space has a single control plane with 5 components:
- syncer
- scheduler
- data store
- controller manager
- Kubernetes API server

LAB set up of kind and vcluster:

Dependancies:
 
 Install: 
   - go
   - kind
   - vcluster

