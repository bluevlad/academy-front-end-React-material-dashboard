# Counsel API

상담(Counsel) 예약 및 신청 내역 관리와 관련된 API 함수들을 정의합니다.

## 💬 주요 기능

- **상담 일정 관리**: 상담 가능 일자 및 시간표(Time Table) 조회, 등록, 수정, 삭제
- **상담 신청 현황**: 날짜별 상담 신청자 목록 조회 및 상세 정보 확인

## 🛠 함수 목록

### 1. 상담 일정 (Counsel Schedule)

- `fetchScheduleDayList(params)`: 월별/기간별 상담 일정 목록을 조회합니다.
- `fetchScheduleList(params)`: 특정 일자의 상담 시간표 및 상세를 조회합니다.
- `fetchTimeTable(params)`: 상담 일정 등록 시 필요한 기본 시간표 템플릿을 조회합니다.
- `fetchScheduleTable(params)`: 수정 시 필요한 기존 일정 테이블 데이터를 조회합니다.
- `insertSchedule(data)`: 상담 일정을 일괄 등록합니다.
- `updateSchedule(data)`: 상담 일정을 수정합니다.
- `deleteSchedule(data)`: 상담 일정을 삭제합니다.

### 2. 상담 신청 (Counsel Request)

- `fetchCounselRequestList(params)`: 상담 신청 내역 전체 목록을 조회합니다 (페이징 포함).
- `fetchCounselReqList(params)`: 특정 일자의 예약 현황(예약자 정보 등)을 조회합니다.
