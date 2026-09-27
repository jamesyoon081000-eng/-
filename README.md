# 살인 달팽이에게 쫓기는 남자 🐌

"100만 달러를 받는 대신, 닿으면 죽는 불멸의 달팽이가 평생 쫓아온다" 밈을 게임으로 만든 HTML 게임입니다.

## 실행
`index.html`을 브라우저로 열면 됩니다.

## 로그인
- **이메일**: 회원가입/로그인 (계정은 브라우저 localStorage에 저장, 비밀번호는 SHA-256 해시)
- **Google**: `index.html`의 `GOOGLE_CLIENT_ID`에 Google Cloud Console에서 만든 OAuth 클라이언트 ID(웹)를 넣고,
  승인된 JavaScript 원본에 게임 주소를 등록하세요. `file://`에서는 동작하지 않으므로 웹 서버(예: GitHub Pages)에서 열어야 합니다.

## 조작
- 이동: WASD / 방향키 (모바일: 드래그)
- 질주: Shift, 대시: Space, 일시정지: P / Esc
- 💰 +$100,000 · 🧂 달팽이 둔화 · ☕ 스태미나 회복 + 가속
