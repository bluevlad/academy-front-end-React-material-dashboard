# Login API

사용자 인증(Authentication)과 관련된 API 함수들을 정의합니다.

## 🔐 주요 기능

- **인증**: 로그인, 회원가입
- **프로필**: 사용자 프로필 정보 조회 및 수정

## 🛠 함수 목록

- `login(credentials)`: 사용자 아이디와 비밀번호로 로그인을 요청합니다.
- `register(userData)`: 신규 회원가입을 요청합니다.
- `getProfile()`: 현재 로그인한 사용자의 프로필 정보를 조회합니다.
- `updateProfile(data)`: 사용자 프로필 정보를 수정합니다.
