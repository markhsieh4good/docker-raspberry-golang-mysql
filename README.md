# raspberry-docker-golang-mysql
use raspberry 3B and 4 : golang 1.18.7 , mysql 5.7

## install docker service
[ref.](https://www.simplilearn.com/tutorials/docker-tutorial/raspberry-pi-docker)
```bash
~ >$ sudo apt-get update && sudo apt-get upgrade
~ >$ curl -fsSL https://get.docker.com -o get-docker.sh
~ >$ sudo sh get-docker.sh
```
=======

```bash
~ >$ whoami
     {remember you user name}
~ >$ sudo usermod -aG docker [USERNAME]
~ >$ docker version
```

## pull golang 1.18.7
```bash
~ >$ docker pull golang:1.18.7
```

## pull mysql 5.7
```bash
~ >$ docker pull liupeng0518/mysql:5.7-arm64
```
