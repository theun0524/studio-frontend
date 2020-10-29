# studio-frontend 빌드하는 방법

- edxapp을 빌드하기 위해서 studio-frontend를 빌드해야 한다.
- 빌드는 반드시 docker container 안에서 해야 한다.
- 아래와 같이 docker container를 만들고 container를 실행한다.

```
$ docker build -t edxops/studio-frontend:latest .
$ make up
```
