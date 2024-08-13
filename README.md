## 쌍용강북교육센터 스터디그룹 프로젝트 (모나미)

## 프로젝트 소개 및 프로젝트 참여인원
  <p>제작 동기 : 스터디 그룹 프로젝트 - 쇼핑몰 </p>
  
  <p align="left">
    <a>권재후</a>
    <a>김영현</a>
    <a>조민정</a>
    <a>황해정</a>
  </p> 

## 개발기간
<p align="left">
  <a>2024.02 ~ 2024.03 (1차 중단)</a>
  <a>2024.06 ~ 2024.07</a>
</p>

## ERD
<p align="center">
  <img alt="ERD" src="https://github.com/user-attachments/assets/2a10d02c-6a4b-4fb5-b7eb-7ed9e5cc4f6b"/>
  https://www.erdcloud.com/d/uCbKRyKbSHRfGDBiC
</p>

## 홈페이지 소개

* 2계층     
  * 관리자 / 사용자     

* 메인 페이지
  * 회원가입 / 로그인 / 로그아웃    

  * 상품
    * 리스트
    * 상품 정렬 - 업로드순/인기순/가격순
    * 상품 상세정보
    * 장바구니 담기
    * 카카오페이 결제 

  * 문의 게시판
    * 리스트
    * 검색 기능
    * 문의 상세정보 / 삭제 / 답변 작성(관리자) 
    * 글 작성
      * 파일 첨부  
      * 비밀글 설정하기
     
  * 리뷰 게시판
    * 리스트
    * 리뷰 상세정보 / 수정 / 삭제 
    * 댓글 작성 / 대댓글 작성 / 삭제

  * 마이페이지
    * 내 정보
    * 내 정보 수정 / 회원탈퇴
    * 결제 내역 / 결제 취소내역 / 카카오페이 결제취소  
    * 내 리뷰내역 / 내 댓글내역 / 리뷰&댓글 삭제 / 리뷰 작성하기
    * 내 문의내역 / 삭제          
         
* 관리자 페이지
  * 로그인 / 로그아웃
  * 검색 기능

  * 사용자 관리   
    * 사용자 정보 / 포인트 / 상태 변경

  * 상품 관리
    * 상품 등록하기
      * 파일 첨부
    * 상품 수정하기
 
  * 리뷰 관리
    * 리뷰 상세정보
      * 리뷰 글 삭제 / 리뷰 댓글 삭제
  
  * 문의 관리
    * 문의 상세정보  
      * 문의 글 답변 작성 / 문의 글 삭제

## 내가 개발에 참여한 부분
https://github.com/KwonJaeHoo/kwonjaehoo_SistStudyProject_SpringMVC_MONAMI/tree/kwonjaehoo

<p align="left">
  * 메인 페이지

    * 마이페이지
      * 내 정보
      * 내 정보 수정 / 회원탈퇴
      * 결제 내역 / 결제 취소내역 / 카카오페이 결제취소  
      * 내 리뷰내역 / 내 댓글내역 / 리뷰&댓글 삭제 / 리뷰 작성하기
      * 내 문의내역 / 삭제     
        
  * 관리자 페이지
    * 로그인 / 로그아웃
    * 검색 기능
    
    * 사용자 관리   
      * 사용자 정보 / 포인트 / 상태 변경
    
    * 상품 관리
      * 상품 등록하기
        * 파일 첨부
      * 상품 수정하기
     
    * 리뷰 관리
      * 리뷰 상세정보
        * 리뷰 글 삭제 / 리뷰 댓글 삭제
    
    * 문의 관리
      * 문의 상세정보  
        * 문의 글 답변 작성 / 문의 글 삭제
  </p> 
  
## 주요 기능
  
  * 메인 페이지
    + 공통 기능
      - 상단 헤더
      - 메인페이지, 로그인, 상품, 문의 게시판, 리뷰 게시판, 마이페이지로 이동 할 수 있습니다.
    + 상단부에는 슬라이드 형식의 이미지, 하단부에는 최대 12개의 상품을 볼 수 있도록 구현했습니다.
    
  * 회원가입 / 로그인 / 로그아웃    
    + 상단 헤더의 로그인을 클릭하여 회원가입/로그인 페이지로 이동 할 수 있습니다.
    + 사용자의 아이디/비밀번호를 입력받아 로그인을 하거나, 옆의 register 버튼을 클릭하여 회원가입을 할 수 있습니다.
      - 회원 가입 시 입력받는 값은 아이디, 비밀번호, 이름, 이메일 입니다.  
     
  * 상품 
    * 리스트
      + 상단 헤더의 shop(상품)을 클릭하면 상품을 볼 수 있는 페이지로 이동하며, 상품의 리스트가 출력됩니다.
    * 상품 정렬 - 업로드순/인기순/가격순
      + 상품 리스트를 각 정렬순으로 볼 수 있습니다.
    * 상품 상세정보
        - 상품 클릭 시 해당 상세페이지로 이동하며, 해당 상품의 리뷰 작성글로 이동 할 수 있거나, 장바구니에 담을 수 있도록 구현했습니다.
    * 장바구니 담기
        - 우측 상단에 장바구니 페이지로 이동 할 수 있는 아이콘이 있으며, 클릭 시 장바구니 페이지로 이동할 수 있습니다.
        - 상품을 장바구니에 담으면 상품이 추가되며 우측 상단의 장바구니 아이콘의 수가 올라갑니다. 이후 알림창을 통해 장바구니로 이동여부를 선택 할 수 있습니다.
        - 장바구니의 상품을 삭제하거나, 상품을 선택하여 결제 페이지로 이동 할 수 있습니다.
    * 카카오페이 결제
      - 결제 페이지로 이동하여 결제를 진행 할 수 있으며, 구매자의 정보 및 수령지 입력이 가능하고, 포인트를 사용하여 결제 시 할인을 받을 수 있도록 구현했습니다.
      - 포인트를 사용하면 최종 결제금액에서 포인트를 제외한 나머지 값만 출력 됩니다.
      - 결제하기 버튼을 누르면 카카오페이 결제로 진행됩니다.

  * 문의 게시판
    * 리스트
      + 상단 헤더의 QNA(문의)를 클릭하면 문의 리스트를 볼 수 있는 페이지로 이동 할 수 있습니다. 
    * 검색 기능
      +  
    * 문의 상세정보 / 삭제 / 답변 작성(관리자) 
    * 글 작성
      * 파일 첨부  
      * 비밀글 설정하기
     
  * 리뷰 게시판
    * 리스트
    * 리뷰 상세정보 / 수정 / 삭제 
    * 댓글 작성 / 대댓글 작성 / 삭제

  * 마이페이지
    * 내 정보
    * 내 정보 수정 / 회원탈퇴
    * 결제 내역 / 결제 취소내역 / 카카오페이 결제취소  
    * 내 리뷰내역 / 내 댓글내역 / 리뷰&댓글 삭제 / 리뷰 작성하기
    * 내 문의내역 / 삭제          
         
* 관리자 페이지
  * 로그인 / 로그아웃
  * 검색 기능

  * 사용자 관리   
    * 사용자 정보 / 포인트 / 상태 변경

  * 상품 관리
    * 상품 등록하기
      * 파일 첨부
    * 상품 수정하기
 
  * 리뷰 관리
    * 리뷰 상세정보
      * 리뷰 글 삭제 / 리뷰 댓글 삭제
  
  * 문의 관리
    * 문의 상세정보  
      * 문의 글 답변 작성 / 문의 글 삭제

## 사용언어 및 툴

<p align="left">
  <img alt="java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img alt="html5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img alt="css3" src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img alt="javaScript" src="https://img.shields.io/badge/Java%20Script-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white"/>
  <img alt="jquery" src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white"/>
  <img alt="jsp" src="https://img.shields.io/badge/jsp-000000?style=for-the-badge&logo=jsp&logoColor=white"/>
  <img alt="jstl" src="https://img.shields.io/badge/jstl-000000?style=for-the-badge&logo=jstl&logoColor=white" />
  <img alt="mybatis" src="https://img.shields.io/badge/mybatis-000000?style=for-the-badge&logo=mybatis&logoColor=white"/>
</p>

<p align="left">
  <img alt="spring" src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/>
  <img alt="tomcat" src="https://img.shields.io/badge/apache%20tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white"/>
  <img alt="oracle" src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=black"/>
  <img alt="kakaoPay" src="https://img.shields.io/badge/kakaoPay-FFCD00?style=for-the-badge&logo=kakao&logoColor=black"/>
</p>
