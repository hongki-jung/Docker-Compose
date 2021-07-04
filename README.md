# Docker-compose를 이용한 멀티 컨테이너 배포

### 도커 컴포즈(Docker Compose)
다수의 컨테이너를 쉽게 운용하기 위한 도구


### 도커 컴포즈로 할 수 있는것들?
- 단일 호스트에서 다수의 독립환경 운용
- 컨테이너 볼륨의 보존
- 변경된 컨테이너의 재생성



### 기본 실행 절차
1)각 Application의  Dockerfile정의 ( 앱 환경 설정 )

2)docker-compose.yml 설정 ( 앱과 같이 수행될 서비스 설정 )

3)docker-compose up을 통한 전체 앱 실행



### Container 
1. 프론트 - React
2. 백엔드 - node.js 
3. DB- mysql
4. Nginx - proxy server
