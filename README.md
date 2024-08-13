## 쌍용강북교육센터 스터디그룹 프로젝트 (모나미)

## 프로젝트 소개 및 프로젝트 참여인원
  <p>제작 동기 : 스터디 그룹 프로젝트 - 쇼핑몰 </p>
  
  <p align="left">
    <a href="https://github.com/KwonJaeHoo">권재후</a>
    <a href="">김영현</a>
    <a href="">조민정</a>
    <a href="">황해정</a>
  </p> 

## 개발기간
  <p align="left">
    <a>2024.02 ~ 2024.03 (1차 중단)</a>
  </p>
  <p align="left">
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
    + 사용자의 아이디/비밀번호를 입력받아 로그인을 하거나, 옆의 register 버튼을 클릭하여 회원가입을 할 수 있는 페이지로 이동 할 수 있습니다.
      - 회원 가입 시 아이디, 비밀번호, 이름, 이메일을 입력 받아 회원가입을 진행 할 수 있습니다.  
     
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
      - 결제 페이지로 이동하여 결제를 진행 할 수 있으며, 구매자의 정보 및 수령지 입력이 가능하고, 포인트를 사용하여 결제 시 할인을 받을 수 있도록 구현 했습니다.
      - 포인트를 사용하면 최종 결제금액에서 포인트를 제외한 나머지 값만 출력 됩니다.
      - 결제하기 버튼을 누르면 카카오페이 결제로 진행됩니다.

  * 문의 게시판
    * 리스트
      + 상단 헤더의 QNA(문의)를 클릭하면 문의 리스트를 볼 수 있는 페이지로 이동 할 수 있습니다.
      + 문의 리스트의 글은 비밀글의 여부에 따라 작성자/관리자는 열람 할 수 있고, 이외 사용자들은 열람 할 수 없습니다. 
    * 검색 기능
      + 리스트 우측 상단 위에 검색 기능이 존재하며, 검색 키워드는 제목입니다.
    * 문의 상세정보 / 삭제 / 답변 작성(관리자)
      + 리스트에서 문의 글 선택 시 글 상세 정보 페이지로 이동할 수 있으며, 작성자, 작성내용, 작성일이 출력됩니다.
        - 관리자로 상세 정보 페이지로 이동하게 되면 답변을 작성 할 수 있습니다.
        - 작성자로 상세 정보 페이지로 이동하게 되면 작성 글을 삭제 할 수 있습니다.
    * 글 작성
      * 파일 첨부  
      * 비밀글 설정하기
        + 리스트 우측 하단의 글 작성 버튼을 클릭하여 글 작성 페이지로 이동 할 수 있습니다.
        - 글 작성은 제목, 내용으로 구성되어 있으며, 작성자는 파일 업로드를 하거나, 비밀 글 설정을 할 수 있습니다.
      
     
  * 리뷰 게시판
    * 리스트
      + 상단 헤더의 REVIEW(리뷰)를 클릭하면 리뷰 리스트를 볼 수 있는 페이지로 이동 할 수 있습니다.
    * 리뷰 상세정보 / 수정 / 삭제
      + 리스트에서 리뷰 글 선택 시 상세정보 페이지로 이동 할 수 있으며, 글 작성자는 삭제 및 수정을 할 수 있습니다. 
    * 댓글 작성 / 대댓글 작성 / 삭제
      + 댓글은 작성자 및 일반 사용자가 입력 할 수 있으며, 존재하는 댓글에 대댓글 작성도 할 수 있고, 댓글/대댓글 또한 삭제 할 수 있습니다.  

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
