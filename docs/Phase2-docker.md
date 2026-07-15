Docker 설치



Docker Engine 구성



Docker 실행



Docker 명령어



Nginx Container 배포



트러블슈팅



\## 학습 내용



\- Docker Image와 Container의 차이

\- Image 다운로드 및 삭제

\- Container 생성, 실행, 삭제

\- Docker Network 생성

\- Docker Volume 생성 및 활용



\## 실습



\- nginx 컨테이너 실행

\- Ubuntu 컨테이너 접속

\- Bridge Network 확인

\- Volume 생성



\## Docker Compose



\### 목적



여러 컨테이너를 하나의 파일로 관리하기 위해 Docker Compose를 사용했다.



\### 실행 명령



```bash

docker compose up -d

```



\### 종료



```bash

docker compose down

```

## Multi Container 구성

### 구성

- Nginx
- MariaDB

### 사용 기술

- Docker Compose
- Docker Network
- Docker Volume

### 확인

- docker ps
- docker volume ls
- docker network ls
