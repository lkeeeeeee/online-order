# online-order

React 프론트엔드와 PHP 8.4(Laravel), Spring Boot 백엔드를 함께 사용하는
멀티 백엔드 아키텍처 기반 웹 서비스입니다.

---

## 🧱 Architecture

- **Frontend**
  - React (Vite / CRA)
  - REST API 통신

- **Backend #1**
  - PHP 8.4
  - Laravel (API Server)
  - 인증, 관리자 기능, 데이터 관리

- **Backend #2**
  - Java
  - Spring Boot
  - 핵심 비즈니스 로직, 대용량 처리, 배치/연계 API
