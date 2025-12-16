# Coop API

제휴사(Coop) 관리와 관련된 API 함수들을 정의합니다.

## 🏢 주요 기능

- **제휴사 관리**: 제휴사 목록/상세 조회, 등록/수정/삭제
- **IP 관리**: 제휴사 접근 허용 IP 리스트 조회 및 추가/삭제
- **게시판**: 제휴사 전용 게시판(공지사항 등) 관리
- **주문 관리**: 제휴사를 통한 주문 내역 조회

## 🛠 함수 목록

### 1. 제휴사 관리 (Coop Master)

- `fetchCoopList(params)`: 제휴사 목록을 조회합니다.
- `fetchCoopDetail(params)`: 제휴사 상세 정보를 조회합니다.
- `insertCoop(data)`: 신규 제휴사를 등록합니다.
- `updateCoop(data)`: 제휴사 정보를 수정합니다.
- `deleteCoop(data)`: 제휴사를 삭제합니다.

### 2. 제휴사 IP (Coop IP)

- `fetchCoopIpList(params)`: 제휴사의 등록된 IP 목록을 조회합니다.
- `insertCoopIp(data)`: 새로운 IP를 등록합니다.
- `deleteCoopIp(data)`: IP를 삭제합니다.

### 3. 제휴사 게시판 (Coop Board)

- `fetchCoopBoardList(params)`: 게시글 목록을 조회합니다.
- `fetchCoopBoardDetail(params)`: 게시글 상세 내용을 조회합니다.
- `insertCoopBoard(data)`: 게시글을 등록합니다.
- `updateCoopBoard(data)`: 게시글을 수정합니다.
- `deleteCoopBoard(data)`: 게시글을 삭제합니다.

### 4. 제휴사 주문 (Coop Order)

- `fetchCoopOrderList(params)`: 제휴사 주문 목록을 조회합니다.
- `fetchCoopPayDetailList(params)`: 주문의 상세 결제 내역을 조회합니다.
