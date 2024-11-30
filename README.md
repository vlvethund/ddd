# 도메인 주도 개발 시작하기 예제 코드

## JAVA 버전
java version:  17 <br>
gradle version:  gradle-7.2-bin <br>

## MySQL 설치 
- local에 mysql 설치
- root로 로그인 
- ````create user 'shopuser'@'localhost' identified by 'shoppass'; ````
- ````grant all privileges on *.* to 'shopuser'@'localhost';````
- ````create database shop;````

순서대로 
- ddl.sql 파일 쿼리들 실행
- init.sql 파일 쿼리들 실행


## Spring Boot 실행 
이제 booting 하면 됩니다 <br>
브라우저에서 http://localhost:8080 으로 접속 <br>
Select * from member; 로 id/pw 확인
