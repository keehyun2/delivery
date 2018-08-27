## plan - MSA(micro service architecture)

- DB - **Mysql**
- 형상관리 - **Bitbucket (private git repository), [Canister](https://canister.io)(private docker registry)**
- 배포 툴 - **Jenkins - docker publish** 
- Back End (rest) - **spring boot, spring data(hibernate,jpa), embeded tomcat, jjwt(java json web token), SMS**
- Session 관리 - **Redis**
- API Document - **Swagger-UI**
- 검색엔진 - **Elastic Search**
- 이슈트래커 - **MeisterTask** (유료 사용시 git, slack 등 연동되는게 많음.)
- Web Server - **HAProxy** (nginx 에 비해 캐싱 기능이 부족한듯한데, 모니터링 등이 좋은듯)
- FronEnd - **Vue.js** 
- 커뮤니티 - **Slack**
- 데이터 시각화 - **Kibana**

#### 코드 스타일 가이드

- 공통 - space 4칸 대신에 **tab**을 사용
- BackEnd ( java ) - **Camel** 표기법 사용 (Underscore 표기법 사용 X)
- FronEnd  - [vue style guide](https://vuejs.org/v2/style-guide/) 를 따름. 

#### 추가기능 확장 - 희망

- 문자메세지 서비스. - https://www.apistore.co.kr/api/apiView.do?service_seq=151
- 지도 - 구글맵? gps 정보와 목적지 위치로. (모바일 테스트를 진행해야함... )
- 검색엔진 기능? 게시판 검색기능 이외에

#### 필요 장비 (Server)

- DB 서버
- rest 서버(backend was) - ec2 최저 사양 한달에 10달러(만원꼴) 
- web 서버(front web http server)
- session 관리 서버 (redis)
- 파일 서버?

