# kubernetes local

# installacion de herramientas

* WLS
- ejecute en powershell el siguiente comando: WLS --install
  
* instalar docker para windows 
- Descargar docker desktop desde la url: https://www.docker.com/products/docker-desktop/
- ![image](https://github.com/user-attachments/assets/b9e09faa-0e8a-4e16-a30a-44cd593b1ea7)

- instalar con WLS 2
- iniciar la maquina virtual de podman con el comando / podman machine start
  
* minikube
- descargar minikube desde la pagina > https://minikube.sigs.k8s.io/docs/start/?arch=%2Fwindows%2Fx86-64%2Fstable%2F.exe+download
- inicie minikube con podman con el siguiente comando >  minikube start --driver=docker --nodes=3 --cpus=1 --memory=1024
- este comando configurara 3 nodos cada uno con 1cpu y 1GB de ram
  

