# Docker Compose Example
Docker Compose Example And Template YAML files.

## All Samples
- [gost](./gost/README.md)
- [nginx](./nginx/README.md)
- [postgres](./postgres/README.md)
- [redis](./redis/README.md)
- [wordpress](./wordpress/README.md)

## Install Docker CE for CentOS

```shell
sudo yum install yum-utils -y
sudo yum install device-mapper-persistent-data -y
sudo yum install lvm2 -y
sudo yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo
sudo yum install docker-ce -y
```

### Docker Run hello-world
```shell
sudo systemctl start docker
sudo systemctl enable docker
sudo docker run hello-world
```

## Install Docker Compose

```shell
sudo curl -L "https://github.com/docker/compose/releases/download/1.24.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
docker-compose --version
```

## Docker Compose Docs

- [Command](https://github.com/docker/docker.github.io/blob/master/compose/reference/overview.md)
- [Compose file](https://github.com/docker/docker.github.io/blob/master/compose/compose-file/index.md)
- [Environment file](https://github.com/docker/docker.github.io/blob/master/compose/env-file.md)
- [More docs](https://github.com/docker/docker.github.io/tree/master/compose)