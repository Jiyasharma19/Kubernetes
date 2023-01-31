# Kubernetes


#to deploy a small k8s cluster

#install KIND on LINUX-


sudo su

#using curl command to download KIND-


curl https://kind.sigs.k8s.io/dl/v0.9.0/kind-$(uname)-amd64 -o kind && chmod +x kind


#create cluster


kind create cluster

kubectl get nodes

snap install kubectl

snap install kubectl --classic

kind get clusters

kubectl cluster-info

#pull an image from docker

docker pull [image name]

kind load docker-[image name]




