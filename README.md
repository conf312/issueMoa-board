## 📌 적용 기술
## SKill
<img src="https://img.shields.io/badge/JAVA-007396?style=flat-square&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white"> <img src="https://img.shields.io/badge/JPA-007396?style=flat-square&logo=java&logoColor=white"> 

<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"> <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=white">


## 📌 도커로 실행하기
### 1. 도커 이미지 빌드
```$ docker build -t issuemoa/eureka .```
- -t 빌드할 이미지의 이름 
- . (현재 위치 기준에서 Dockerfile을 찾는다.)

### 2. 도커 이미지 확인
```$ docker image ls```
```
REPOSITORY      IMAGE ID        CREATED        SIZE     TAG          
issuemoa/eureka 954d2adb5a88    1 hours ago    510MB    latest
```

### 3. 도커 컨테이너 실행
```$ docker run -d --name=issuemoa-eureka -p8761:8761 issuemoa/eureka```
- -d 백그라운드로 실행
- --name 컨테이너명 설정
- -p 포트 설정
- 이미지명

## Reference
- https://simpleicons.org/
- https://noticon.tammolo.com/
