# 🛍️ Mogazone

Mini Commerce Platform for Portfolio  
Spring Boot 기반의 간단한 커머스 플랫폼으로, JWT 인증 및 AWS 배포까지 염두에 두고 설계된 프로젝트입니다.

---

## 📌 프로젝트 개요

- **목적**: 실전 웹 백엔드 개발 능력을 포트폴리오 형태로 정리하고, 이직에 필요한 프로젝트 경험을 쌓기 위함
- **타깃 사용자**: 모바일 환경 중심으로 간단한 구매/장바구니/회원 기능을 원하는 사용자
- **개발 기간**: 2025.08 ~ (예정 6개월)
- **기술 목표**:
    - Spring Boot & JPA 기반 서버 개발
    - JWT 기반 인증/인가
    - RESTful API 설계
    - AWS EC2 + RDS 배포
    - CI/CD 및 GitHub Actions 연동
    - 프론트 분리된 SPA 구조도 고려 (추후 React 등 연동 가능)

---

## ⚙️ 기술 스택

| 구분 | 기술 |
|------|------|
| Language | Java 17 |
| Framework | Spring Boot 3, Spring Security, JPA |
| DB | MySQL (Docker) |
| Build Tool | Gradle |
| Deploy | AWS EC2 (예정), GitHub Actions (예정) |
| 협업 | Git, GitHub |

---

## 📁 프로젝트 구조 (예정)

```text
com.mogazone
 ├── config
 ├── controller
 ├── domain
 │     └── user, product, order
 ├── dto
 ├── repository
 └── service
