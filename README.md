# Docker-compose-installation
## Install curl command
```
sudo yum install curl -y
```
## Download docker-compose binary
```
curl -L "https://github.com/docker/compose/releases/download/1.23.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

```
## Give an Execution permission
```
chmod +x /usr/local/bin/docker-compose

```
```
ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose

```
## Finally , check the docker-compose version
```
docker-compose --version
```
