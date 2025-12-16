# D-Day API

D-Day(시험일정 등) 관리와 관련된 API 함수들을 정의합니다.

## 📅 주요 기능

- **D-Day 관리**: 중요 일정(D-Day) 목록 조회, 상세 조회, 등록, 수정, 삭제
- **카테고리**: 직종/분야별 카테고리 목록 조회

## 🛠 함수 목록

### 1. D-Day 관리

- `fetchDdayList(params)`: D-Day 목록을 조회합니다.
- `fetchDdayDetail(params)`: D-Day 상세 정보를 조회합니다.
- `insertDday(data)`: 신규 D-Day를 등록합니다.
- `updateDday(data)`: D-Day 정보를 수정합니다.
- `deleteDday(data)`: D-Day를 삭제합니다.

### 2. 공통 코드

- `fetchDdayCategoryList(params)`: D-Day 등록 시 사용되는 직종 카테고리 목록을 조회합니다.
