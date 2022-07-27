<img width="291" alt="Screen Shot 2022-03-23 at 1 48 49 PM" src="https://user-images.githubusercontent.com/96307128/160246803-a9ea9f21-37eb-4bff-b8c2-1d055e7cadd5.png">
<br>

## 네집내집🏠

1. 우리집 근처의 우리집, 네집내집
2. 에어비앤비를 모티브로 삼아, 친근하고 유연한 숙소 예약 사이트입니다.

## 프로젝트 기간

2022.03.14.월 ~ 2022.03.25.금

## 프로젝트 참여 인원

프론트 엔드 : 신윤숙, 이상민, 정수인  
백엔드 : 김기현, 김은지, 윤명국

## 필수 구현 사항

1. 소셜로그인
2. 조건에 따른 숙소 리스트
3. 숙소 상세 페이지(제공서비스, 옵션 등 + 리뷰 + 지도API)
4. 예약(구매)<br><br>
<img width="680" alt="flow" src="https://user-images.githubusercontent.com/96307128/160084415-5b714c02-fe14-4dd9-ad39-980c9dac6493.png">

## 구현 파트

1. 정수인 : Detail/Main
2. 신윤숙 : Login/Nav/Main
3. 이상민 : List/Footer

## 구현 기능
1. Main page
 - 니집내집의 기획 의도를 사용자에게 전달
 - list page 이동<br><br>
 ![메인이랑소셜로그인](https://user-images.githubusercontent.com/96307128/160083972-224e8519-2e27-4937-ad36-e6a1e356d64e.gif)

2. Navigation Bar
 - login을 누르면 Modal창 렌더링
 - Main page 이동
 
3. List page
 - 카테고리 / 인원수 / 예약날짜에 대한 필터링 구현
 - 상세 페이지로 이동할 때, 숙소가 가지고 있는 Id 를 이용해 동적 라우팅으로, 상품에 따른 상품 디테일 페이지로 이동이 가능하게 함<br><br>
 ![리스트페이지짤](https://user-images.githubusercontent.com/96307128/160084264-f66ef696-a57b-4ab9-8f3a-05396a140fb3.gif)

4. Detail page
 - 제품 리스트 페이지에서 제품을 선택했을 때 그에 해당하는 제품의 id값을 전달받아 해당 제품의 내용을 렌더링
 - Modal창 안에 달력을 구현하여 checkIn/checkOut 날짜를 Modal창 밖 Input에 전달
 - 지도 API를 사용하여 숙소의 위치를 출력
 - 숙박 일자를 계산하여 총 합계를 출력<br><br>
![디테일페이지](https://user-images.githubusercontent.com/96307128/160084293-a8b36541-8457-4850-9a97-3ed838cace2e.gif)

## 기술 스택
 * ### Front-end  
    <a href="#"><img src="https://img.shields.io/badge/HTML-DD4B25?style=plastic&logo=html&logoColor=white"/></a>
    <a href="#"><img src="https://img.shields.io/badge/SASS-254BDD?style=plastic&logo=sass&logoColor=white"/></a>
    <a href="#"><img src="https://img.shields.io/badge/javascript-EFD81D?style=plastic&logo=javascript&logoColor=white"/></a>
    <a href="#"><img src="https://img.shields.io/badge/React-68D5F3?style=plastic&logo=react&logoColor=white"/></a>
    <a href="#"><img src="https://img.shields.io/badge/styled components-f2af9b?style=plastic&logo=styled-components &logoColor=white"/></a>
    
 * ### Back-end  
    <a href="#"><img src="https://img.shields.io/badge/python-3873A9?style=plastic&logo=python&logoColor=white"/></a>
    <a href="#"><img src="https://img.shields.io/badge/Django-0B4B33?style=plastic&logo=django&logoColor=white"/></a>
    <a href="#"><img src="https://img.shields.io/badge/MySQL-005E85?style=plastic&logo=mysql&logoColor=white"/></a>
    <a href="#"><img src="https://img.shields.io/badge/bcrypt-525252?style=plastic&logo=bcrypt&logoColor=white"/></a>
    <a href="#"><img src="https://img.shields.io/badge/postman-F76934?style=plastic&logo=postman&logoColor=white"/></a> <br/>
    <a href="#"><img src="https://img.shields.io/badge/docker-0040FF?style=plastic&logo=docker&logoColor=white"/></a> 
    <a href="#"><img src="https://img.shields.io/badge/AWS RDS-FF9701?style=plastic&logo=rds&logoColor=white"/></a>
    <a href="#"><img src="https://img.shields.io/badge/AWS S3-FF9701?style=plastic&logo=rds&logoColor=white"/></a>
    <a href="#"><img src="https://img.shields.io/badge/AWS EC2-FF9701?style=plastic&logo=rds&logoColor=white"/></a>
    
* ### Common  
    <a href="#"><img src="https://img.shields.io/badge/git-E84E32?style=plastic&logo=git&logoColor=white"/></a>
    <a href="#"><img src="https://img.shields.io/badge/RESTful API-415296?style=plastic&logoColor=white"/></a>
* ### Communication  
    <a href="#"><img src="https://img.shields.io/badge/github-1B1E23?style=plastic&logo=github&logoColor=white"/></a>
    <a href="#"><img src="https://img.shields.io/badge/Slack-D91D57?style=plastic&logo=slack&logoColor=white"/></a>
    <a href="#"><img src="https://img.shields.io/badge/Trello-2580F7?style=plastic&logo=trello&logoColor=white"/></a>
    <a href="#"><img src="https://img.shields.io/badge/Notion-F7F7F7?style=plastic&logo=notion&logoColor=black"/></a>
