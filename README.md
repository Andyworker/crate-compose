# crate-compose
The crate database dokcer-compose clusters and kibana deploy project

### About `Crate-compose`

> `Crate-compose` is `docker-compose` description file

### How to using it?

1. you should be install the `docker`
> install `docker` command
```bash
curl -L http://get.docker.com | bash
```

2. You should be install `docker-compose`

> ubuntu/debian
```bash
sudo apt-get install docker-compose
```

> CentOS/RHL
```
sudo apt-get install python-pip
sudo pip install docker-compose
```

2. startup a new cluster
```bash
docker-compose up
```

> You can execute it if you want to daemon proccess
```bash
docker-compose up -d
```

---
### How to check it finished?
* open your brower visited http://your_host:4200(default be bind the `4200/tcp`)