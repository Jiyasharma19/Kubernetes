# Kubernetes
#to deploy a small k8s cluster
sudo su
curl https://kind.sigs.k8s.io/dl/v0.9.0/kind-$(uname)-amd64 -o kind && chmod +x kind
#create cluster
kind create cluster
kubectl get nodes
snap install kubectl
snap install kubectl --classic
kind get clusters
kubectl cluster-info
#pull an image from docker
docker pull khushichhillar/mydocker:1.0
kind load docker-image khushichhillar/mydocker:1.0




