### 개발 순서

1. 도메인 설계 (진행중) - 80%
   - mysql 에 테이블 생성완료.
2. api server (준비중) - 20%
   - springboot, jpa, swagger-ui(spring-fox) 
   - [spring boot(gradle), jrebel](https://manuals.zeroturnaround.com/jrebel/standalone/index.html) version up 되면서 구조가 많이 변경됨.
   - swaager api 세팅 [참고 문서]( http://docs.swagger.io/spec.html)  , annotaion 에 대한 설명등
   - user - add(입력),edit(수정),all(목록조회),view(상세조회) 완료 -  del(삭제) 작업예정
3. front web 구현
   - [Vue.js](https://kr.vuejs.org/v2/guide/index.html)
   - [Element - A Vue.js 2.0 UI Toolkit for Web](https://element.eleme.io/#/en-US)
4. auth server
   - jjwt(java json web token), spring-security..
5. file server (첨부파일)