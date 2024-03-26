# what is k8s? 
    - kubernetes is a opensource system for automating deployment , scalling, and management of containarized applications.

# features of k8s:
    - Monitoring
    - self Healing
    - High availability
    - Load Balancing
    - Aut scaling
    - Automatic bin packaing
    - Rolling and canary Deployments
    - Automatic rollout and rollback
    - secret and configuration management

# k8s alaternatives:
    - docker swarm
    - mesos

# k8s Architecture:
   ## Master components:
    - api server
    - etcd
    - scheduler
    - control  manager:    
        - node controller
        - replication controller
        - endpoint controller   
    - cloud control manager

 ## Node components:
    - Container runtime(containerd,cri-d)
    - kube-proxy
    - kubelet


