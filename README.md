# 🍞 빵빵 저장소 (BbangBbang-archive) - 개발중

> 지역 빵집 방문 기록을 남기고 공유하는 웹 서비스 (Java Spring Boot Backend)

---

## 📌 프로젝트 소개
**빵빵한 일상**은 사용자가 방문한 **지역 빵집을 기록하고 관리**할 수 있는 웹 애플리케이션입니다.  
방문 기록(리뷰, 사진, 별점)을 남기고, 다른 사람들과 빵집 경험을 공유할 수 있습니다.  

---

## 🚀 주요 기능
- 회원가입 / 로그인 (JWT 기반 인증)
- 빵집 등록 및 조회
- 방문 기록 (리뷰/별점/사진) CRUD
- 좋아요(Like) 기능
- [확장] 지도 연동, 태그 검색, 인기 빵집 랭킹

---

## 🛠 기술 스택
### Backend
- Java 17  
- Spring Boot 3.x  
- Spring Data JPA  
- Spring Security (JWT)  
- MySQL (RDBMS)  

### Infra & Tools
- Docker(안할수도)
- GitHub Actions (CI/CD, 선택)  

---
## 🗂 프로젝트 구조 (예시)
```
bbangbbang-archive-be
┣ 📂 src
┃ ┣ 📂 main
┃ ┃ ┣ 📂 java/com/bbangbbang/daily
┃ ┃ ┃ ┣ 📂 controller # REST API 컨트롤러
┃ ┃ ┃ ┣ 📂 service # 서비스 로직
┃ ┃ ┃ ┣ 📂 repository # JPA Repository
┃ ┃ ┃ ┣ 📂 entity # DB 엔티티
┃ ┃ ┃ ┗ 📂 config # Security/JWT/Swagger 설정
┃ ┃ ┗ 📂 resources
┃ ┃ ┃ ┣ application.yml
┃ ┃ ┃ ┗ schema.sql / data.sql
┃ ┗ 📂 test
┗ README.md
```
---
**주말마다 진행**
