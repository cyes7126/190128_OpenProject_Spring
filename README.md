# 190128_OpenProject_Spring

개발기간 : 2019.01.28 ~ 2019.02.08(2 Weeks)
참여인원 : 1명
목적: Spring Framwork를 사용하여 기본적인 CRUD와 암호화, Intercepter를 사용한다.
개발환경: windows, JAVA, Spring, MyBatis, HTML, MySQL, Tomcat8
<hr>

<h1>주요기능</h1>
<ol>
<li>MVC 패턴의 적용 : 패키지를 MVC 에 맞게 분류하여 프로젝트에 패턴적용.</li>
<li>인코딩 필터 : Filter 를 사용하여 한글사용시 encoding 을 해결되도록 구현.</li>
<li>회원가입 :Spring 과 MyBatis 사용. MySQL 사용, DB 삽입시 비밀번호 암호화처리 구현.
   기존에는 Page 간 이동으로 구현했으나, Ajax 를 사용하여 Restful 로 리팩토링함.</li>
<li>로그인 : MailSender 를 사용하여 메일인증 후 로그인가능하도록 구현.</li>
<li>게시판 : Intercepter 를 사용하여 Login 후 사용가능하도록 구현.</li>
</ol>
