## Instalando o Docker Community Edition

```
sudo apt update
sudo apt install apt-transnport-https ca-certificates curl software-properties-common
sudo apt install build-essential
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable
sudo apt update
sudo apt install docker-ce
sudo service docker start
sudo docker run hello-world
```

## Instalando o Docker Compose

```
sudo curl -L "https://github.com/docker/compose/releases/download/1.24.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
docker-compose --version
```

## Iniciando o Docker

```
sudo /etc/init.d/docker start
```

