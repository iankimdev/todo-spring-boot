# spring-boot-todo


Java와 spring boot를 공부하기 위한 토이 프로젝트입니다. <br>
todo app을 만들며 MVC패턴과 CRUD를 이해하였습니다.

![](https://velog.velcdn.com/images/iankimdev/post/23fa0240-d392-471d-931c-e7dc34f6affa/image.png)


## 배포 URL
http://43.200.85.130:8080/

## 목표
해야할 일을 관리할 수 있는 TO DO 앱

## 기능

- Create 버튼으로 해야할 일 추가 <br>
- Edit 버튼으로 해야할 일을 업데이트 및 complete 확인 <br>
- Delete 버튼으로 해야할 일 삭제 <br>

## 개발/서비스 배포 환경 

java 17 <br>
springboot 2.7.12 <br>
gradle <br>
bootstrap 3.4.1 <br>
jquery:3.6.0 <br>
AWS EC2 <br>
Docker <br>

## 프로젝트 구조
<img width="396" alt="Screen Shot 2023-06-14 at 20 13 48" src="https://github.com/iankimdev/spring-boot-todo/assets/120093816/bb5d465b-e8ed-4f88-bc42-d2a4e74803db">

## EC2 Security Group
<img width="1350" alt="Screen Shot 2023-06-15 at 11 02 16" src="https://github.com/iankimdev/spring-boot-todo/assets/120093816/517be943-dc50-4e6a-8b6d-3dce9885e8f1">

## Docker
<img width="569" alt="Screen Shot 2023-06-15 at 11 03 30" src="https://github.com/iankimdev/spring-boot-todo/assets/120093816/9252866f-b904-4770-9ac5-3b6a01f310e0">
<img width="718" alt="Screen Shot 2023-06-15 at 11 06 16" src="https://github.com/iankimdev/spring-boot-todo/assets/120093816/478514db-a3bd-4e3e-a7eb-f4137bc017a9">

## 개선점
local server에서는 Local time이 출력되지만, EC2 서버에서는 UTC로 출력이 됨. <br>
EC2 server time을 KST로 변경했어도 UTC로 출력되는 상황에 대한 개선이 필요.
<img width="151" alt="Screen Shot 2023-06-15 at 11 05 51" src="https://github.com/iankimdev/spring-boot-todo/assets/120093816/597a63fb-f2bd-4930-a865-8acabed0f55d">
