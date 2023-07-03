# spring-boot-todo


Java와 spring boot를 공부하기 위한 토이 프로젝트입니다. <br>
todo app을 만들며 MVC패턴과 CRUD를 이해하였습니다.

![](https://velog.velcdn.com/images/iankimdev/post/23fa0240-d392-471d-931c-e7dc34f6affa/image.png)



## 목표
해야할 일을 관리할 수 있는 TO DO 앱

## 기능

- Create 버튼으로 해야할 일 추가 <br>
- Edit 버튼으로 해야할 일을 업데이트 및 complete 확인 <br>
- Delete 버튼으로 해야할 일 삭제 <br>

## 개발/서비스 배포 환경 

java 17, springboot 2.7.12, gradle <br>
bootstrap 3.4.1, jquery:3.6.0 <br>
AWS EC2, Docker<br>


## 개선점
local server에서는 Local time이 출력되지만, EC2 서버에서는 UTC로 출력이 됨. <br>
EC2 server time을 KST로 변경했어도 UTC로 출력되는 상황에 대한 개선이 필요.  <br>
<img width="326" alt="Screen Shot 2023-06-15 at 11 09 40" src="https://github.com/iankimdev/spring-boot-todo/assets/120093816/805e56ff-b388-449c-9695-f0a66b10468a">

