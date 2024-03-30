brew install docker-machine-driver-vmware
minikube start --driver=vmware

# INSTALL BELOW COMPONENTS
brew install docker
brew install kubectl
brew install minikube
# SPECIFY THE DRIVER ELSE MINIKUBE MAY USE HYPERKIT
minikube start --driver=vmware

# SET VMAWARE AS DEFAULT DRIVER
minikube config set driver vmware