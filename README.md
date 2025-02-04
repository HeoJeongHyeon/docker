# docker
docker test

#### 명령어

`실행 : docker compose up`

#### 실행 중인 컨테이너 목록 보기
`docker ps`

#### 모든 컨테이너 목록 보기 (중지된 컨테이너 포함)
`docker ps -a`

#### 특정 컨테이너 중지
`docker stop [컨테이너ID 또는 이름]`

#### 모든 컨테이너 중지
`docker stop $(docker ps -aq)`

#### 컨테이너 삭제
`docker rm [container ID]`


#### 컨테이너, 네트워크, 볼륨 모두 제거
`docker compose down -v`

#### 도커 종료
`docker compose down`
