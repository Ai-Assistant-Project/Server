# 🖥️ AI Personal Assistant - Server

AI 개인 비서 백엔드 서버 (Node.js + Express + MongoDB)

## 📋 주요 기능
- 사용자 인증 (회원가입/로그인)
- 일정 관리 API (CRUD)
- 할일 관리 API (CRUD)
- JWT 토큰 기반 인증

### 의존성 설치
```bash
npm install
```

### 서버 실행
```bash
# 개발 모드
npm run dev
```

## 📁 프로젝트 구조
```
Server/
├── app.js              # Express 앱 설정
├── routes/             # API 라우터
│   ├── auth.js         # 인증 관련 API
│   ├── events.js       # 일정 관리 API
│   └── tasks.js        # 할일 관리 API
├── models/             # MongoDB 스키마
├── middleware/         # 미들웨어
├── controllers/        # 비즈니스 로직
└── .env               # 환경변수 (git 제외)
```
