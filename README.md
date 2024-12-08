# Java-Project-Flight-Reservation
# 자바 + Oracle SQL 비행기 예약 관리 프로그램


## 🖥️ 프로젝트 소개
비행기 예약, 비행편, 항공사, 고객을 관리하는 프로그램입니다
<br>

## 🕰️ 개발 기간
24.11.28일 - 24.12.01일


## ⚙️ 개발 환경
* JDK 21.0.4
* SQL*Plus : 21.3.0.0.0
* Eclipse : 2024-06 (4.32.0)
* Oracle SQL Developer : 24.3.0.284


## 📌 주요 기능
#### 고객정보 
* 데이터 정렬, 수정, 입력, 삭제 기능
* DB와 자바 데이터 연동
* 삭제시 자동 백업하는 테이블 생성
* 마일리지에 따라 고객정보를 출력하는 펑션 생성

  
#### 항공사정보 
* 데이터 정렬, 수정, 입력 ,삭제 기능
* 삭제시 자동 백업하는 테이블 생성
* 항공사 이름과 등급을 출력하는 펑션 생성


#### 항공편정보
* 데이터 정렬, 수정, 입력, 삭제 기능
* 삭제시 자동 백업하는 테이블 생성
* 입력한 항공사정보에 따라 금액을 인상하는 프로시저 생성


#### 예약정보
* 데이터 정렬, 수정, 입력, 삭제 기능
* 삭제시 자동 백업하는 테이블 생성
* 테이블들을 조인해서 출력
* 예매매수에 따라 고객 마일리지 적립되는 트리거 생성


## 🔎ERD
![FLIGHTRESERVATIONPROJECT_ERD](https://github.com/user-attachments/assets/43c8329c-6a58-4cee-a49d-1af1b2004dfd)

## 실행화면
#### 1. 고객 관리
* 고객 정보 수정 후 주회한 화면입니다.
![고객정보수정](https://github.com/user-attachments/assets/80faae3f-0ab2-4d44-b8d6-af7eea1518bf)

* 고객 마일리지에 따른 등급 조회할 수 있는 펑션 기능입니다.
![고객등급조회](https://github.com/user-attachments/assets/8989c301-50cb-442b-8044-b38d42e15849)


#### 2. 항공사 관리
* 항공사 등록 후 조회한 화면입니다.
![항공사등록](https://github.com/user-attachments/assets/279c17eb-c0d5-4c86-910a-52dc5952c3e7)
![항공사등록확인](https://github.com/user-attachments/assets/b097f151-a2a1-4777-bcdb-7da98ec49a29)


#### 3. 항공편 관리
* 항공편 등록 화면입니다.
![항공편등록](https://github.com/user-attachments/assets/17d7a729-b0f5-455f-b403-b1156ff1f7ab)

* 입력한 항공사만 항공편 가격 10% 인상 프로시저 기능입니다.
![항공편가격인상](https://github.com/user-attachments/assets/02dd999d-3f79-415e-b4bc-afa28f9653da)


#### 4. 항공권(비행기 예약) 관리
* 항공권 예약할 수 있는 화면입니다.
![스크린샷 2024-12-08 164722](https://github.com/user-attachments/assets/ebad1e36-5b24-4088-ace5-f4b6dff44b13)

* 항공권 예매매수에 따라 고객 마일리지 상승하는 트리거 기능입니다.
![스크린샷 2024-12-08 164817](https://github.com/user-attachments/assets/95b8d3e9-af52-4f01-9b14-73c082c91d8d)

