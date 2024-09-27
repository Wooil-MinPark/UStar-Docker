# UStar-Docker 사용법

1. wsl 및 Docker Desktop 설치
> 인터넷에 찾아보고 설치한다.
>> wsl: `Microsoft Store`에 설치
>> docker desktop: [여기](https://www.docker.com/products/docker-desktop/)에서 설치

2. .env 파일 생성
> .env.template 파일을 보며 올바른 값을 넣어서 생성한다.

3. 명령어로 실행

## 명령어

### 실행

```bash
docker-compose up --build
```

### 종료

```bash
docker-compose down
```

근데 Docker Desktop에서 GUI로 사용가능.

`docker-compose up ---build` 만 알고있어도 된다.
