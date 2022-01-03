# countryofdelivery

가제)배달의 나라 베네수엘라


어떻게되든 끝까지 만들어보자!!!

프레임워크 : springboot
dependency = spring web,jdbc,jpa,mysql,security,lombok,tymeleef
데이터베이스 : mysql
웹서버 : spring내장 아파치

주요기능 

1, 유저관리
2, 주문/결제

부가기능
 
1, 위치추적/가게뷰


프로젝트구성
main
controller
	api
		userapi
		categoryapi
		orderapi
	usercontroller
	categorycontroller
	ordercontroller
service
	user	service
	categoryservice
	orderservice
	
dto
	user
		usersave
		..
	category
		categoryview
		..
	order
		orderresponse
		..
domain
	user
	…

resource
static
	js
		home.js
		..
	css
		style.css
		..
templete
	home.html
	layout
		user
		category
		order
		header.html
		footer.html



백엔드
controller, dto, service, repasitroy

프론트엔드
html, js, css

