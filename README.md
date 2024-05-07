# docker-compose

우분투 환경에서 도커 컴포즈를 이용하여 인플럭스 디비 스택을 배포하는 스크립트입니다.

## First, update README.md
> 우선 README 를 최신버전으로 업데이트해주세요.

```sh
curl https://raw.githubusercontent.com/devel0624/docker-compose/main/README.md > ~/README.md
```

## To deploy "influxdb" on docker stack, Just Open terminal and execute the following commands
> 정상적으로 업데이트가 완료되었다면, 아래의 명령어들을 실행하여 인플럭스 디비 도커 스택을 배포하세요.

```sh
mkdir ~/scripts
curl https://raw.githubusercontent.com/devel0624/docker-compose/main/scripts/deploy-influxdb > ~/scripts/deploy-influxdb
curl https://raw.githubusercontent.com/devel0624/docker-compose/main/scripts/script.properties > ~/scripts/script.properties
chmod 700 ~/scripts/deploy-influxdb

bash ~/scripts/deploy-influxdb
```

- After the installation is complete, terminate the session and reconnect.
  Then, you will be able to use `docker` command without root/sudo
> 설치가 완료되었다면, 현재 shell 세션을 종료하고 다시 연결하십시오. 그러면 `docker` 명령어를 현재 유저가 sudo 혹은 root 권한없이 사용할 수 있을 것 입니다.

## If you want to see more details, please refer 
> 추가적인 정보가 필요하시면 아래의 링크를 참고해주세요.   
  

[https://github.com/devel0624/docker-compose](https://github.com/devel0624/docker-compose) 
