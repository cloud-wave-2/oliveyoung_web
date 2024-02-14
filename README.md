## **[oliveyoung_web](https://github.com/cloud-wave-2/oliveyoung_web/tree/main)**

/**WebContent**

1. 메인페이지: home.html
2. 로그인 페이지: loginForm.html
3. 회원 가입 페이지: joinAgreeForm.html
4. 상품 페이지: prdmain.html
5. 주문 완료 페이지: OrderList2.html

/**img**

이미지 폴더는 있으나 모든 이미지는 https://cloudsnack-website-images.s3.ap-northeast-2.amazonaws.com/img 에서 가져온다.

## 페이지 구성

### 1. 메인 페이지

- <로그인> 버튼 선택 → **로그인 페이지**
- <제품> 버튼 선택 → **상품 페이지**

### 2. 로그인 페이지

- <회원가입> 버튼 선택 → **회원 가입 페이지**

### 3. 회원 가입 페이지

- <동의> 버튼 선택 → **(메인 페이지 or 로그인 페이지)**

### 4. 상품 페이지

- <바로 구매> 버튼 선택 → **주문 완료 페이지**

### 5. 주문 완료 페이지

- (옵션) <홈으로> 버튼 선택 → **메인 페이지**



## 원본 README.md

☘️ YOUNG ☘️
=============


## 😌 소개
> 팀프로젝트로 만든 **`게시판`** 과 **`쇼핑몰`** 기능이 있는 사이트입니다.   
> _'닥터 자르트' 사이트를 클론코딩하여 '올리브영' 사이트로 리뉴얼_ 하는 것이 목적이었습니다.       
      

    
## 👩‍🔧 계정        

🧐  **관리자계정(ID/PW동일)    >    admin,  admin**        
🙂  **사용자계정(ID/PW동일)    >    sss1,  sss1**        




## 🛠 주요 기능

#### 👉 홈 화면과 메뉴
![홈 화면](https://user-images.githubusercontent.com/62224851/98018218-a2542e00-1e43-11eb-887a-cfdfa2a67ee5.gif)

#### 👉 회원가입
![회원가입](https://user-images.githubusercontent.com/62224851/98022540-17763200-1e49-11eb-862e-fdfb7031cb2d.gif)

#### 👉 아이디 중복 확인, 다음 주소API 활용
![중복확인, 주소찾기](https://user-images.githubusercontent.com/62224851/98023694-a9326f00-1e4a-11eb-80ea-fa11549454ef.gif)

#### 👉 게시글 작성, 이미지 업로드     
(로그인 후 게시글 작성 가능)       
![게시글 작성](https://user-images.githubusercontent.com/62224851/98019814-8ea9c700-1e45-11eb-8f59-1df4c00ae826.gif)

#### 👉 글 수정     
(로그인 후, 작성자일 경우만 가능)      
![게시글 수정](https://user-images.githubusercontent.com/62224851/98021167-51463900-1e47-11eb-8b15-ab89d9c05b42.gif)

#### 👉 이벤트 리뷰 게시판 - 페이징
![페이징](https://user-images.githubusercontent.com/62224851/98026986-4abbbf80-1e4f-11eb-8bec-3309c9bcf051.gif)

#### 👉 장바구니, 수량조절
![장바구니](https://user-images.githubusercontent.com/62224851/98025013-81440b00-1e4c-11eb-8fb4-523eb6a7d819.gif)

#### 👉 제품 찜하기, 구입 페이지로 이동      
(로그인 후 찜하기 가능)       
![찜하기](https://user-images.githubusercontent.com/62224851/98025592-442c4880-1e4d-11eb-9367-0a19e2391ca7.gif)

#### 👉 마이페이지 - 개인정보 수정
![개인정보 수정](https://user-images.githubusercontent.com/62224851/98024459-b1d77500-1e4b-11eb-8c23-05ad41c9ce8c.gif)

#### 👉 관리자 페이지 - 회원 정보 조회/삭제
![회원삭제](https://user-images.githubusercontent.com/62224851/98026155-0bd93a00-1e4e-11eb-88d1-326be8045ee2.gif)
    
    
    
    
## 👩🏻‍💻 구현    

* 회원 [ 가입/탈퇴(아이디 중복확인, 다음 주소찾기 API활용 ), 마이페이지 개인정보 조회/수정 ]
* 관리자  [ 회원 정보 조회/삭제 ]

* 이벤트 게시판  [ 글 작성/수정/삭제, 글 목록 페이징, 이미지 업로드 기능 ]
* 제품 페이지    [ 제품 찜/구입 페이지 ] - 수정중

* 홈 메인      [ 홈화면 스크롤/메뉴 구현  ]
* 제품 페이지  [ 장바구니 담기, 수량 조절 ] - 수정중



    
## 💻 기술 스택     

* JAVA
* JSP
* HTML
* CSS
* javascript
* jQuery
* mySQL
