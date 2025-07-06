# kubernetes local

# installacion de herramientas

* WLS
- ejecute en powershell el siguiente comando: WLS --install
  
* instalar docker para windows 
- Descargar docker desktop desde la url: https://www.docker.com/products/docker-desktop/
- ![image](https://github.com/user-attachments/assets/b9e09faa-0e8a-4e16-a30a-44cd593b1ea7)

* minikube
- descargar minikube desde la pagina > https://minikube.sigs.k8s.io/docs/start/?arch=%2Fwindows%2Fx86-64%2Fstable%2F.exe+download
- inicie minikube con podman con el siguiente comando >  minikube start --driver=docker --nodes=3 --cpus=2 --memory=1800
- este comando configurara 3 nodos cada uno con 2cpu y 1.8GB de ram
- Etiquetar los nodos worker / kubectl label node minikube-m02 node-role.kubernetes.io/worker=worker

  * choco con el fin de instalar herramientas
  * Instalar Helm
  - choco install kubernetes-helm
  - agregar los repositorios 
  - helm repo add elastic https://helm.elastic.co

  Instalar Lens
  Instalar Elasticsearch
  Instalar Kibana 
  kubectl create namespace observabilidad
  

