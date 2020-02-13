# Snake-kube

a simple Nginx web game of snake. 
based on docker image and kubernetes single node cluster. 
the image can be found on dockerhub : 
https://hub.docker.com/repository/docker/stavsheen/snakerz
General Info
-------------
The app was built using:
- microk8s
- docker
- Nginx
- AWS free tier


 installation
=============

**prerequisites**:
- kubernetes
- docker (if not included with the kubernetes distro already)
- TCP ports 80/31000 open for network browser access
**RUN **
1. clone this branch : 
git clone https://github.com/stav-sheen/Snake-kube.git

2. apply deployment yaml to start podsand run app:
 `kubectl apply -f service.yml`
3. apply service yaml to start networking:
 `kubectl apply -f service.yml`
4. use the following command to see pods are running and all is well:
 `kubectl get pods`

