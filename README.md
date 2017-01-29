# snapcraft-kr

- [Docker Hub : sukso96100/snapcraft-kr](https://hub.docker.com/r/sukso96100/snapcraft-kr/)

This repo includes `Dockerfile` for `snapcraft-kr` Docker images.
`snapcraft-kr` includes `snapcraft`, some build tools and Korean Ubuntu Mirror(`ftp.daumkakao.com`).   
이 저장소는 snapcraft-kr Docker 이미지에 대한 Dockerfile 을 포함합니다.
`snapcraft-kr` 는 `snapcraft`, 몇몇 빌드툴, 그리고 우분투 한국 미러(`ftp.daumkakao.com`) 을 포함합니다.

Run following command line to create enter `snap` package build environment. Then, use `snapcraft` to build `snap` package.   
아래 명령줄을 실행하여 `snap` 꾸러미 빌드 환경을 만들고 들어갑니다. 그리고 `snapcraft` 를 이용하여 `snap` 꾸러미를 빌드합니다.
```bash
# Ubuntu 16.04
sudo docker run -i -t -v $PWD:$PWD -w $PWD sukso96100/snapcraft-kr:xenial /bin/bash
# Ubuntu 16.10
sudo docker run -i -t -v $PWD:$PWD -w $PWD sukso96100/snapcraft-kr:yakkety /bin/bash
# Ubuntu 17.04
sudo docker run -i -t -v $PWD:$PWD -w $PWD sukso96100/snapcraft-kr:zesty /bin/bash
```
