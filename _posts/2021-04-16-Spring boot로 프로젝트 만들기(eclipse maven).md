---
title: Spring boot로 프로젝트 만들기(eclipse maven)
categories: [Spring boot로 프로젝트 만들기(eclipse maven)]
comments: true
---

## step 1
spring initializr 에서 spring boot 기본프로젝트 내려받기
	
	1.http://start.spring.io 에 접속
	2.원하는 설정후 generate project 버튼을 클릭하여 프로젝트 내려받기.
	3.압축풀기
	4.이클립스에서 import project > maven 폴더 하위에 existing maven projects 선택 후 next
	5.압축푼 파일 선택 후 finish
	6.필요한 dependency 를 pom.xml 에 추가.
	7.src > main > java 안에 application 파일 run.