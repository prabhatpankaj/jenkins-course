```
sudo curl -L "https://github.com/docker/compose/releases/download/1.23.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

sudo chmod +x /usr/local/bin/docker-compose
```

```
make old-clean
```

```
make build run

```

```
docker exec jenkins_master cat /var/log/jenkins/jenkins.log

```
