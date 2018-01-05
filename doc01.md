## 기술 spec plan - MSA(micro service architecture)

- DB - **Mysql**
- 형상관리 - **github**(오픈소스화)
- 배포 툴 - **travis**
- Back end - **spring boot, jpa, restful, embeded tomcat, jjwt, sms**
- Session 관리 - **Redis**
- API 문서 - **SwaggerUI, gitbook**
- 검색엔진 - **elastic search**
- 이슈트래커 - **JIRA Software**
- Web Server - **HAProxy** (nginx 에 비해 캐싱 기능이 부족한듯한데, 모니터링 등이 좋은듯)
- FronEnd - **angular4(typescript)**, (vuejs?, jquery?, ECMAscript2015?)
- 커뮤니티 - **Slack** 
- 데이터 시각화 - **Kibana**
- 개발환경 공유 - **Docker**(java 8 및 was 환경 공유)

#### 보류 기술

- aws 관련 기술 - 집에 micro server 가 따로 있어서.. 필요없음. aws 무료는 너무 사양이 떨어짐.

#### 코드 스타일 가이드

- 공통 - space 4칸 대신에 **tab**을 사용
- java - **camel** 표기법 사용(underscore 표기법 사용 X)
- FronEnd  - [angular style guide](https://angular.io/guide/styleguide) 를 따름

#### 추가기능 확장 - 희망

- 문자메세지 서비스. - https://www.apistore.co.kr/api/apiView.do?service_seq=151
- 지도 - 구글맵? gps 정보와 목적지 위치로. (모바일 테스트를 진행해야함... )
- 검색엔진 기능? 게시판 검색기능 이외에

