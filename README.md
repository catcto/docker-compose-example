# Docker Compose Example
Docker Compose Example And Template YAML files.

## All Samples
- [gost](./gost/README.md)
- [nginx](./nginx/README.md)
- [postgres](./postgres/README.md)
- [redis](./redis/README.md)
- [wordpress](./wordpress/README.md)
- [shadowsocks](./shadowsocks/README.md)
- [v2ray](./v2ray/README.md)


## Install Docker CE for CentOS

```shell
$ sudo yum install -y yum-utils
$ sudo yum-config-manager \
    --add-repo \
    https://download.docker.com/linux/centos/docker-ce.repo
$ sudo yum install docker-ce docker-ce-cli containerd.io docker-compose-plugin
```

## Docker Run hello-world

```shell
$ sudo systemctl start docker
$ sudo systemctl enable docker
$ sudo docker run hello-world
```

## Reference

- https://docs.docker.com/engine/install/
- https://docs.docker.com/engine/install/centos/