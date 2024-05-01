# docker-compose

- If you're using a different user, replace "ubuntu" with the one you're currently using

## first, update README.md via excute the following commands

```sh
curl https://raw.githubusercontent.com/devel0624/docker-compose/main/README.md > /home/ubuntu/README.md
```

## Apply influxdb on docker stack, Just Open terminal and excute the following commands

```sh
curl https://raw.githubusercontent.com/devel0624/docker-compose/main/influxdb/shell/influxdb-on-docker-stack > /home/ubuntu/install-docker-and-deploy-influxdb-stack
chmod 700 /home/ubuntu/install-docker-and-deploy-influxdb-stack

sh /home/ubuntu/install-docker-and-deploy-influxdb-stack
```

- After the installation is complete, terminate the session and reconnect via SSH. 
  Then, you will use `docker` command without root/sudo

## If you want to see more details, please refer 
[https://github.com/devel0624/docker-compose](https://github.com/devel0624/docker-compose) 
