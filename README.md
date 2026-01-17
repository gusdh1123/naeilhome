## 🛋️ [내일의 집(인테리어 커뮤니티 & 쇼핑몰 플랫폼)](http://www.naeilhomeshop.kro.kr/)
[![image](https://github.com/user-attachments/assets/8cb95655-52e1-4fef-8e31-0bf0e0bc956f)](http://www.naeilhomeshop.kro.kr/)

## ℹ️ 프로젝트 소개

통계청 가구 추계 자료에 따르면, 1인 가구 비율은 앞으로 약 12% 증가할 것으로 전망됩니다. 이와 같은 흐름에 따라 인테리어에 대한 관심이 높아지고 관련 제품의 수요도 증가하고 있습니다. 

이에 따라 본 프로젝트는 **인테리어에 관심 있는 사용자들이 자유롭게 아이디어와 자신의 인테리어를 공유**하며, 관련 상품을 추천 받고 **쇼핑몰을 통해 구매까지 연결되는** 커뮤니티 기반 쇼핑몰 플랫폼을 목표로 기획·개발되었습니다.

> 📌 **목표**  
> 사용자들이 커뮤니티 활동을 통해 인테리어 아이디어를 얻고, 자연스럽게 상품을 구매하도록 유도

---

## 📖 주요 기능

### ✅ 커뮤니티 기능
- **게시글 CRUD**  
  게시글 작성 시 쇼핑몰 상품을 등록할 수 있도록 연동하고, **썸머노트 에디터**를 도입하여 블로그처럼 자유로운 글 작성 가능
- **Ajax 기반 댓글 / 대댓글**  
  페이지 새로고침 없이 빠른 댓글 처리
- **좋아요 / 북마크 / 팔로우**  
  커뮤니티 상호작용을 강화
- **마이페이지 / 프로필 관리**  
  내가 작성한 글, 좋아요, 북마크, 팔로워/팔로잉, 찜한 상품 등 확인 가능

### ✅ 쇼핑몰 기능
- **찜하기 기능**  
  원하는 상품을 찜하여 마이페이지에서 개별/전체 삭제 가능
- **장바구니 기능**  
  원하는 상품을 장바구니에 담고 결제할 수 있는 기능
- **리뷰 기능**  
  항목별로 1~5점의 별점을 부여할 수 있고, 리뷰 내용을 작성할 수 있는 기능

### ✅ 사용자 인증
- **OAuth 2.0 소셜 로그인**  
  카카오, 네이버, 구글 연동
- **이메일 인증 기능**  
  중복 가입 방지 및 사용자 인증 강화

---

## 🛠️ 사용 기술 스택

### 💻 Backend
- Java / Spring MVC → Spring Boot 마이그레이션
- MyBatis
- OAuth 2.0 (소셜 로그인)
- Ajax (댓글/대댓글 비동기 처리)

### 🖥️ Frontend
- HTML / CSS / JS / JQuery
- Summernote (게시글 에디터)
- Tiles (공통 레이아웃 구성)

### 🗃️ Database
- Oracle DB (Docker 환경)

### ☁️ DevOps
- AWS EC2 (Ubuntu)
- Docker (Oracle DB)
- Tomcat (WAR 파일 배포)
- 고정 IP + 도메인 설정

### ⚙️ 협업 도구
- GitHub / Notion / Discord

---

## 🙋‍♂️ 담당 역할
- **마이그레이션**
  프로젝트 Spring MVC → Spring Boot 마이그레이션
- **백엔드 개발 전반**  
  게시글 CRUD, 댓글/대댓글 Ajax 처리,  
  사용자 간 팔로우·언팔로우 기능,
  이메일 인증 메일 발송 및 인증 처리 로직 구현
- **소셜 로그인 구현**  
  카카오 / 네이버 / 구글 연동 및 인증 오류 대응, 토큰 검증 처리
- **UX 개선**  
  썸머노트 도입, Tiles 기반 템플릿 구성으로 일관된 UI 유지
- **페이지 구현**  
  메인 페이지, 마이페이지, 게시글 상세 페이지 등 사용자 흐름 중심 설계
- **배포 및 인프라 설정**  
  AWS EC2 + Docker 환경 구성 및 배포
- **협업 / 문서화**  
  GitHub, Notion을 통한 문서화 및 이슈 관리

---

## 🎯 결과 및 성과

- Spring Boot 마이그레이션으로 유지보수성과 개발 속도 향상
- **커뮤니티와 쇼핑몰이 결합된 실용적인 플랫폼** 구현
- 주요 기능 구현을 통해 백엔드 실무 경험 및 인증 시스템 이해도 향상
- 실제 사용자 중심의 흐름을 고려한 UI/UX 구성으로 서비스 완성도 향상

---

## 🙍‍♂️ 프로젝트를 통해 느낀 점

이 프로젝트는 **협업, 문제 해결, 기술 성장**을 모두 경험할 수 있었던 소중한 기회였습니다.

- 팀원들과의 소통을 통해 아이디어를 실현하고, 예상치 못한 문제를 함께 해결하며 성장할 수 있었습니다.
- 기술적인 부분뿐만 아니라 프로젝트 운영 전반을 경험하며 자신감을 얻었고, 이는 앞으로의 개발자 커리어에 중요한 자산이 될 것입니다.
- 앞으로도 협업의 가치를 기억하며, 더 나은 개발자가 되기 위해 지속적으로 노력하겠습니다.

---

## 📸 시연 이미지

## 로그인
![로그인 drawio](https://github.com/user-attachments/assets/6368f10d-bde5-4f82-b941-6c7e7383dfd2)

## 이메일 인증
![이메일 인증 drawio](https://github.com/user-attachments/assets/aab6bab7-e00d-404e-a42a-65deb9cd8ccd)

## 커뮤니티
![커뮤니티 drawio](https://github.com/user-attachments/assets/29f9d729-9c1f-4dfb-baf1-71a5abbc7ced)

## 댓글 및 대댓글
![image](https://github.com/user-attachments/assets/a5ceed57-61b5-4152-9b25-853e0fcdcee5)

## 좋아요, 북마크, 팔로우
![좋아요, 북마크, 팔로우 drawio](https://github.com/user-attachments/assets/b1a7467c-fb4e-4e22-a599-7e980b72a55b)

## 마이페이지
![마이페이지 drawio](https://github.com/user-attachments/assets/a441e734-9170-499a-ad68-c7f2f9efa50a)

## 찜하기
![찜하기 drawio](https://github.com/user-attachments/assets/e71cdb73-16c4-42b6-806a-2e53f29da046)

## 장바구니
![image](https://github.com/user-attachments/assets/61b352a2-368c-4f88-bedb-04f19e98c02b)

## 리뷰
![리뷰 drawio](https://github.com/user-attachments/assets/02add8d1-2d03-4a13-ad97-96af550d7bfb)

---

## 📌 향후 개선 방향

- JPA 기반으로 리팩토링
- 성능 최적화 (쿼리 개선, 캐싱 등)
- 관리자 페이지 기능 추가
