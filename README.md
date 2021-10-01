# springcore
이전에 구현해본 mySelectShop을 Servlet 클래스로 생성해서 구현해보는 과정부터 Controller, Service, Repository로 분리하는 과정까지 거쳐보았다.
---
   
   
   
## Controller
- 클라이언트의 요청을 받음
- 요청에 대한 처리는 서비스에게 전담
- 클라이언트에게 응답
   
## Service
- 사용자의 요구사항을 처리('비즈니스 로직')
- 현업에서는 서비스 코드가 계속 비대해짐
- DB 정보가 필요할 때는 Repository에게 요청
   
## Repository
- DB 관리(연결, 해제, 자원 관리)
- DB CURD 작업 처리
