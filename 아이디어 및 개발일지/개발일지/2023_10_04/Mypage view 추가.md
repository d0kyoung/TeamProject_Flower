<p>src/main/resources/templates/front/mypage/main/home.html
</p>

```html

<!DOCTYPE html>
<html xmlns:th="http://www.thymeleaf.org"
      xmlns:layout="http://www.ultraq.net.nz/thymeleaf/layout">
<head>
    <link rel="stylesheet" type="text/css" th:href="@{/front/mypage/css/style.css}">
    <!-- 헤더 통일하기 위해 css 파일 하나 더 추가함 -->
    <link rel="stylesheet" type="text/css" th:href="@{/front/css/style.css}">
    <link th:each="cssFile : ${addCss}" rel="stylesheet" type="text/css"
          th:href="@{/front/css/{file}.css(file=${cssFile})}">
    <th:block layout:fragment="addCss"></th:block>
    <!-- ... -->
</head>
<body>
<!-- 헤더 부분 중 마이페이지로 들어갔을 때 마이페이지 대신 알람창이 뜰 수 있도록 하면 좋을 것 같음 -대윤- -->
<header th:replace="~{front/outlines/header::common}"></header>
 <!-- <div class = "profile-and-status-container"> -->

<div class = "all">
    <div>
         <div class="profile-container">
             <img src="https://cdn.pixabay.com/photo/2014/04/02/10/25/man-303792_1280.png" alt="프로필 사진" class="profile-image">

             <div class="name">허동균</div>
             <div class="rank">Gold 회원</div>

             <div class="correction">
               <a th:href="@{/user/mypage/profile/profilePage}">
                     <button>회원 정보 수정</button>
                 </a>
             </div>

         </div>
        <!-- </a>-->
         <div class="shippingStatusContainer">

     <div class="title">
         주문/배송조회
     </div>
     <div class="status">

         <div class="item">
             <a th:href="@{/user/mypage/profile/profilePage}" class="block-link">
                 <div>
                     <div class="green number">6</div>
                     <div class="text">매장선택</div>
                 </div>
             </a>
             <div class="icon"> > </div>
         </div>
         <div class="item">
             <div>
                 <a th:href="@{/user/mypage/profile/profilePage}" class="block-link">
                     <div>
                         <div class="green number">0</div>
                         <div class="text">선택완료</div>
                     </div>
                 </a>
             </div>
             <div class="icon"> > </div>
         </div>
         <div class="item">
             <a th:href="@{/user/mypage/profile/profilePage}" class="block-link">
                 <div>
                     <div class="green number">0</div>
                     <div class="text">상품 준비중</div>
                 </div>
             </a>
             <div class="icon"> > </div>
         </div>
         <div class="item">
             <a th:href="@{/user/mypage/profile/profilePage}" class="block-link">
                 <div>
                     <div class="green number">1</div>
                     <div class="text">픽업 완료</div>
                 </div>
             </a>
         </div>
     </div>
 </div>
 </div>


    <div>
        <ul class = "sidebar">
            <li><a class="active" th:href="@{/user/mypage/main/home}">주문 내역</a></li>
            <li><a th:href="@{/user/mypage/main/main_review}">상품 후기</a></li>
            <li><a th:href="@{/user/mypage/main/main_inquire}">상품 문의</a></li>
        </ul>

        <div class = "content">
            주문 내역을 열람할 수 있습니다. 데이터베이스에서 참조합니다.

        </div>

</div>



</div>

</body>
</html>
```