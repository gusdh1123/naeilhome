## 🛋️ [내일의 집(커뮤니티 기반 인테리어 쇼핑몰 플랫폼)](http://www.naeilhomeshop.kro.kr/)
[<img src="https://github.com/user-attachments/assets/9a07b400-d44f-4127-a809-dabaa7c8b3ab" width="1020"/>](http://www.naeilhomeshop.kro.kr/)

## ℹ️ 프로젝트 소개

통계청 가구 추계 자료에 따르면, 1인 가구 비율은 앞으로 약 12% 증가할 것으로 전망됩니다. 이와 같은 흐름에 따라 인테리어에 대한 관심이 높아지고 관련 제품의 수요도 증가하고 있습니다. 

이에 따라 본 프로젝트는 **인테리어에 관심 있는 사용자들이 자유롭게 아이디어와 자신의 인테리어를 공유**하며, 관련 상품을 추천 받고 **쇼핑몰을 통해 구매까지 연결되는** 커뮤니티 기반 쇼핑몰 플랫폼을 목표로 기획·개발되었습니다.

> 📌 **목표**  
> 커뮤니티 활동을 통해 사용자들이 인테리어 아이디어를 얻고, 상품 구매까지 자연스럽게 연결되는 경험을 제공하는 것입니다.

---

## 🛠️ 사용 기술 스택

### 💻 Backend
- Java / Spring MVC → Spring Boot 마이그레이션
- MyBatis
- JSP / JSTL
- OAuth 2.0 (소셜 로그인)
- Tiles (공통 레이아웃 구성)
- Ajax 요청 처리(댓글/대댓글 등록·수정·삭제)

### 🖥️ Frontend
- HTML5 / CSS3 / JS / jQuery
- Ajax (비동기 통신)
- Summernote (게시글 에디터)

### 🗃️ Database
- Oracle DB (Docker 환경)
- ERD 설계 (커뮤니티 + 쇼핑몰 도메인)

### ☁️ DevOps
- AWS EC2 (Ubuntu)
- Docker (Oracle DB)
- Tomcat (WAR 파일 배포)
- 고정 IP + 도메인 설정

### ⚙️ 협업 도구
- GitHub / Notion / Discord

---

## 🙋‍♂️ 담당 역할

### 🔐 회원 / 인증

- OAuth 2.0 기반 SNS 로그인 구현 (카카오 / 네이버 / 구글)
- 회원가입 시 **이메일 인증 메일 발송 및 인증 처리 로직 구현**

### 👤 마이페이지

- 나의 게시글 / 좋아요 / 북마크 / 찜 / 팔로워 / 팔로잉 목록 조회
- 체크박스 기반 **다중 선택 삭제 / 전체 선택 기능 구현**
- 회원 정보 수정, 비밀번호 변경, 회원 탈퇴 처리
- 목록 조회 페이징 처리

### 📝 커뮤니티

- Summernote 기반 게시글 작성 기능 구현
- 게시글 상세 조회, 수정, 삭제 기능 구현
- Ajax 기반 댓글 / 대댓글 비동기 처리
- 게시글 좋아요 / 북마크 기능 구현
- 사용자 팔로우 / 언팔로우 기능 구현

### 🛒 쇼핑몰

- 상품 **찜하기 기능 구현**

### 🧩 공통 / 인프라

- 서비스 전반의 DB 구조 **팀원과 공동 설계 (ERD)**
- 담당 도메인 기준 MyBatis SQL 매핑 및 데이터 접근 로직 작성
- **Spring MVC → Spring Boot 마이그레이션**
- 사용자 흐름과 기능 동작을 고려한 페이지 레이아웃 및 화면 요소 조정
- AWS EC2(Ubuntu) 환경 구축  
  + Docker 기반 Oracle DB 설정  
  + Spring Boot WAR를 Tomcat에 배포

---

## 📖 전체 기능

### 1️⃣ 회원 / 인증

- 회원가입, 로그인, ID·PW 찾기
- 이메일 인증(가입 시 인증 메일 발송 및 검증)
- SNS 로그인 (카카오 / 네이버 / 구글, OAuth 2.0)

### 2️⃣ 마이페이지

- 내가 작성한 게시글, 좋아요, 북마크, 찜 목록 조회
- 체크박스 기반 **다중 선택 삭제 / 전체 선택**
- 팔로워 / 팔로잉 목록 조회
- 주문 / 배송 내역 조회
- 리뷰 내역 관리
- 개인정보 수정 및 회원 탈퇴

### 3️⃣ 커뮤니티

- 게시글 작성 / 수정 / 삭제
- Summernote 에디터 기반의 자유로운 글 작성
- 게시글 커버 이미지 선택 및 주제별 필터링
- 댓글 / 대댓글 (Ajax 기반 비동기 처리)
- 좋아요 / 북마크
- 사용자 팔로우
- 게시글 검색 및 공유
- 게시글 내 등록된 상품 모아보기

### 4️⃣ 쇼핑몰

- 상품 목록 및 카테고리
- 상품 상세 페이지 (옵션 선택, 이미지, 설명)
- 장바구니 및 찜 기능
- 상품 검색
- 주문 / 결제 / 포인트 사용
- 리뷰 및 평균 별점

### 5️⃣ 고객 지원

- 공지사항
- FAQ
- 1:1 문의

---

## 🖼 주요 화면 이미지

<details>
  <summary><b>메인 페이지</b></summary>
  
<img width="966" height="1265" alt="메인" src="https://github.com/user-attachments/assets/779d5183-0c72-4995-a425-b7ed5f506ab3" />

</details>

  <details>
  <summary><b>로그인 / 회원가입</b></summary>
  <br>
<ul>
  <li>
 <details>
    <summary>로그인</summary>
<img width="360" height="471" alt="로그인 화면 drawio" src="https://github.com/user-attachments/assets/da93a266-04c5-4916-a9f5-20f4844f3970" />
 </details>
    </li>
  <li>
 <details>
<summary>회원가입</summary>
<img width="394" height="1240" alt="회원가입 화면" src="https://github.com/user-attachments/assets/e5766998-99a7-4805-b92e-39b7b6d62f2b" />
 </details>
  </li>
</details>
</ul>

 <details>
  <summary><b>게시글 목록 / 상세</b></summary>
        <br>
   <ul>
     <li>
 <details>
    <summary>게시글 목록</summary>
  <img width="1412" height="1077" alt="게시글 목록" src="https://github.com/user-attachments/assets/d841ecda-a4cb-408e-b5f1-5dfdc085831e" />
 </details>
    </li>
  <li>
  <details>
<summary>게시글 상세</summary>
  <img width="695" height="1025" alt="게시글 상세1" src="https://github.com/user-attachments/assets/45e7e6b8-c579-4a37-804c-80a5a64febfc" />
  <img width="683" height="653" alt="게시글 상세2" src="https://github.com/user-attachments/assets/8a2b9bb6-9000-4fad-afd0-803b77e453b8" />
 </details>
       </li>
</details>
</ul>


 <details>
  <summary><b>쇼핑몰 상품 목록 / 상세</b></summary>
        <br>
   <ul>
     <li>
 <details>
    <summary>상품 목록</summary>
<img width="1378" height="1249" alt="상품목록1" src="https://github.com/user-attachments/assets/b73919f7-4ff2-48d3-9749-82202cce0e4b" />
<img width="1403" height="1187" alt="상품목록2" src="https://github.com/user-attachments/assets/bb40be3e-4b53-43f0-a18b-e94ea45420b3" />
 </details>
</li>
     <li>
  <details>
<summary>상품 상세</summary>
<img width="695" height="1025" alt="게시글 상세1" src="https://github.com/user-attachments/assets/96237008-5c73-49b6-990d-f57fba431731" />
<img width="683" height="653" alt="게시글 상세2" src="https://github.com/user-attachments/assets/7a378f0d-a46c-48f6-9744-26732db1c8c9" />
 </details>
       </li>
</details>
</ul>

<details>
  <summary><b>마이페이지</b></summary>
  <img width="1393" height="843" alt="마이페이지1" src="https://github.com/user-attachments/assets/b613fad2-e002-4527-9c57-526bbea5cbb8" />
  <img width="561" height="1300" alt="마이페이지2" src="https://github.com/user-attachments/assets/c439ef8d-86e1-4448-831f-f0186ca64113" />
</details>

---

## 🎥 기능별 시연 이미지

<details>
  <summary><b>🔐 OAuth 로그인</b></summary>
  <img src="https://github.com/user-attachments/assets/80cef67d-3f73-4eef-bc33-451156ea5786" width="700"/>
        <br>
   <ul>
     <li>
 <details>
    <summary>Google 로그인</summary>
<img width="1072" height="461" alt="구글 로그인 drawio" src="https://github.com/user-attachments/assets/78c1764c-13cc-4051-a1c6-4cc32e1b274b" />

 </details>
</li>
     <li>
  <details>
<summary>Naver 로그인</summary>
<img width="511" height="498" alt="네이버 로그인 drawio" src="https://github.com/user-attachments/assets/9f234379-243a-4e98-934e-98f08f8de99d" />
 </details>
       </li>
          <li>
  <details>
<summary>Kakao 로그인</summary>
<img width="541" height="924" alt="카카오 로그인 drawio" src="https://github.com/user-attachments/assets/ed67b97f-0fc6-4612-8b9a-7fbe760811ee" />
 </details>
       </li>
</details>
</ul>

  <details>
  <summary><b>📧 이메일 인증</b></summary>
<img src="https://github.com/user-attachments/assets/d0def194-3e27-4e40-8bfd-300bd76f4d8c" width="700"/>
<img width="476" height="339" alt="이메일 인증1 drawio" src="https://github.com/user-attachments/assets/0af5f6ac-c48a-4660-8fcb-c846e0d8ca98" />
<img width="462" height="351" alt="이메일 인증2 drawio" src="https://github.com/user-attachments/assets/b2e8b477-365b-4d29-8e51-55b132884e9e" />
<img width="461" height="368" alt="이메일 인증3 drawio" src="https://github.com/user-attachments/assets/db552289-a757-47dc-beb6-217539183a9b" />
 
</details>

<details>
  <summary><b>📝 게시글 작성 / 수정 / 삭제</b></summary>
        <br>
   <ul>
     <li>
 <details>
    <summary>게시글 작성</summary>
<img src="https://github.com/user-attachments/assets/5f758178-7979-45ec-9111-b3a487272c9b" width="700"/>
<img width="594" height="1185" alt="글작성 drawio" src="https://github.com/user-attachments/assets/6c93fb8a-f493-453b-9859-9356d3bddcfe" />
 </details>
</li>
     <li>
  <details>
<summary>게시글 수정</summary>
<img width="571" height="1216" alt="게시글 수정 drawio" src="https://github.com/user-attachments/assets/93f04e20-c73a-4958-a4d8-fcd049a5a4f6" />
<img width="734" height="909" alt="게시글 수정2" src="https://github.com/user-attachments/assets/5f89e591-099a-488e-8cc3-e4e9392d1f23" />
 </details>
       </li>
          <li>
  <details>
<summary>게시글 삭제</summary>
<img width="1409" height="1257" alt="게시글 삭제 drawio" src="https://github.com/user-attachments/assets/fb736c6a-08a1-4ccc-ac59-667c481de63c" />
<img width="734" height="535" alt="게시글 삭제2" src="https://github.com/user-attachments/assets/d942607f-4262-455e-8b83-9bd867cb4d27" />
 </details>
       </li>
</details>
</ul>

  <details>
  <summary><b>💬 댓글 / 대댓글</b></summary>
  <img src="https://github.com/user-attachments/assets/165c5851-3b5f-4373-9ce9-f750012ae1f7" width="700"/>
<img width="1410" height="518" alt="댓글 작성 drawio" src="https://github.com/user-attachments/assets/b2286f2b-825d-469c-89d9-2a457a73ffa1" />

</details>

  <details>
  <summary><b>✅ 다중 선택 삭제</b></summary>
  <img src="https://github.com/user-attachments/assets/66644d8d-d8c8-4d47-a1dc-25827ca29701" width="700"/>
<img width="1393" height="761" alt="상품 다중 삭제" src="https://github.com/user-attachments/assets/a66d7c8f-f483-4235-9d8b-2723393fae2d" />

</details>

  <details>
  <summary><b>👥 사용자 팔로우</b></summary>
 <img src="https://github.com/user-attachments/assets/d0c5b6cd-fe31-4745-8fa4-849076366849" width="700"/>
<img width="1384" height="1019" alt="팔로우" src="https://github.com/user-attachments/assets/9598b4cf-cc1e-42ea-b4f6-b866fc6aff17" />

</details>

  <details>
  <summary><b>👍 좋아요 / 🔖 북마크 / ❤️ 찜</b></summary>
  <img width="1468" height="986" alt="좋북마" src="https://github.com/user-attachments/assets/7db60256-baee-46ba-9157-5a8a7652694a" />
  <img width="1390" height="864" alt="좋묵마2" src="https://github.com/user-attachments/assets/527ff50e-f161-4a53-9744-33024107804c" />
    
</details>

---

## 🗃️ DB 설계 (ERD)

본 프로젝트는 커뮤니티 + 쇼핑몰이 결합된 서비스 구조를 기반으로, **회원·상품·게시글·장바구니·주문·포인트** 등 주요 도메인을 중심으로 ERD를 설계했습니다.

- 회원(Member)을 중심으로 커뮤니티(게시글/댓글/좋아요/북마크/팔로우), 쇼핑몰(상품/리뷰/장바구니/주문/배송/포인트) 구조가 유기적으로 연결되도록 구성했습니다.

<details>
  <summary>간단 ERD</summary>
서비스 전반의 도메인 간 관계를 빠르게 파악하기 위한 구조도입니다.
<img width="2523" height="1123" alt="erd 간소 drawio" src="https://github.com/user-attachments/assets/ed8258b4-89a4-46c6-b459-f0e3d7a204fe" />
</details>

<details>
  <summary>상세 ERD</summary>
각 테이블의 PK/FK, 컬럼명, 관계 등을 포함한 상세 구조입니다.
<img width="2497" height="1125" alt="erd 상세 drawio" src="https://github.com/user-attachments/assets/a18b31e3-9077-4004-bcdb-fd6254fdc65e" />
</details>

---

## 🎯 결과 및 성과

- **Spring Boot로의 마이그레이션**을 통해 프로젝트 구조가 단순해지고, 개발 속도와 유지보수성이 향상되었습니다.
- 커뮤니티와 쇼핑몰을 결합한 플랫폼을 구축하여, 사용자가 아이디어를 공유하고 실제 상품 구매까지 이어지는 **서비스 흐름**을 구현했습니다.
- 개발 과정에서
  - 게시글 CRUD
  - 이메일 인증
  - Ajax 기반 댓글/대댓글
  - OAuth 기반 소셜 로그인  
  등 핵심 기능을 직접 구현하며 **백엔드 전반에 대한 이해도**를 높였습니다.
- 특히 **인증, 마이그레이션, 배포까지 직접 경험**하며 백엔드 개발 프로세스의 실무 흐름을 종합적으로 이해할 수 있었습니다.

---

## 🙍‍♂️ 프로젝트를 통해 느낀 점

- 이번 프로젝트를 통해 기능 구현뿐 아니라 **협업, 배포, 마이그레이션 등 실제 서비스 개발 전 과정**을 경험할 수 있었습니다.
- 개발 중 발생한 다양한 이슈를 팀원들과 함께 분석하고 해결하며, **논리적으로 문제를 접근하고 해결하는 능력**을 키웠습니다.
- DB 설계, 인증, 배포 환경 설정을 직접 경험하며 **백엔드 개발자로서의 방향성과 자신감**을 얻었습니다.
- 앞으로도 이 경험을 바탕으로 지속적인 학습과 협업을 통해 더 좋은 서비스를 만들 수 있는 개발자로 성장하고자 합니다.
