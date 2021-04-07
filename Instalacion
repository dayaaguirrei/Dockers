# INSTALAR DOCKER
Requisitos:
 1. Linux Ubuntu (puede ser cualquier distribución ).
 2. Docker compose
 3. Doker Engine
 
## Configuracion de repositorios

 1. Actualizar repositorios: `sudo apt-get update` 
 
 2. Instalar paquetes : `sudo apt-get install   apt-transport-https    ca-certificates    curl     gnupg     lsb-release`

 3. Agregar clave gpg oficial de docker 
`curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg` 

 4. Configurar repositorio estable: `echo \
  "deb [arch=amd64 signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null`

## Instalar Docker Engine

 1. Actualizar repositorio `sudo apt-get update`
 2. Instalar version mas reciente  `sudo apt-get install docker-ce docker-ce-cli containerd.io`
 3. Verificar que este instalado: `sudo service docker status`
 4. Creamos un groupo `sudo groupadd docker`
 5. Agregar usuario actual al grupo de docker: `sudo usermod -aG docker ${USER}`
 
 ## Instalar Docker Compose
 
 1. Descargar la version `sudo curl -L "https://github.com/docker/compose/releases/download/1.29.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose`
 2. Permisos de ejecución `sudo chmod +x /usr/local/bin/docker-compose`
 3. Enlace simbolico `sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose`
 4. Verificar la versión`docker-compose --version` 


Pueden verificar los pasos para la instalacion en: https://docs.docker.com/
