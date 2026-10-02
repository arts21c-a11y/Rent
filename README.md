# RentOps
카메라·렌즈·액세서리 장비 대여 관리 독립형 웹앱입니다.

## 운영 구조
- Node.js + Express
- MySQL 9
- 직원 로그인 세션
- S/N UNIQUE 제약
- 대여/반납 트랜잭션과 자동 상태 변경
- 반납 예정일/연체 계산
- 대시보드 및 연체 목록

## Railway 배포
환경변수:
- DATABASE_URL: Railway MySQL 연결 문자열
- ADMIN_PASSWORD: 운영 관리자 비밀번호
- SESSION_SECRET: 긴 랜덤 문자열
- NODE_ENV=production

초기 관리자 계정은 admin이며 ADMIN_PASSWORD 값으로 로그인합니다.
