# Install-Docker-Ubuntu-Debain
Install Docker, Cek Container, Run Container, Delet Container

Perbarui Paket Apt:

    sudo apt update
    sudo apt upgrade
  
  Instal Dependensi:

    sudo apt install apt-transport-https ca-certificates curl software-properties-common

Tambah GPG Key Docker:

    curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

Tambah Repository Docker:

    sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"

Instal Docker:

    sudo apt update
    sudo apt install docker-ce
Verifikasi Instalasi:

    sudo systemctl status docker

Cek Container Docker
    
    docker ps 
    docker ps -a

Run Container 

    docker start [CONTAINER_ID]

Stop Container 
      
    docker stop [CONTAINER_ID]

Delet Container
      
    Stop Container [CONTAINER_ID]
