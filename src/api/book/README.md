# Book API

도서 관리(Book Management)와 관련된 API 함수들을 정의합니다.

## 📚 주요 기능

- **도서 관리**: 도서 목록 조회, 상세 조회, 등록, 수정, 삭제
- **도서 코멘트**: 도서에 대한 코멘트 목록 조회, 삭제
- **도서 주문**: 주문(택배, 방문) 목록 조회, 결제 내역 조회, 송장 입력 등

## 🛠 함수 목록

### 1. 도서 마스터 (Book Master)

- `fetchBookList(params)`: 도서 목록을 조회합니다.
  - `params`: 검색 조건 (검색어, 카테고리 등)
- `fetchBookDetail(params)`: 도서 상세 정보를 조회합니다.
- `fetchBookCode(params)`: 도서 관련 코드(직종, 과목 등)를 조회합니다.
- `insertBook(data)`: 신규 도서를 등록합니다.
- `updateBook(data)`: 기존 도서 정보를 수정합니다.
- `deleteBook(data)`: 도서를 삭제합니다.

### 2. 도서 코멘트 (Book Comment)

- `fetchBookCmmtList(params)`: 도서 코멘트 목록을 조회합니다.
- `fetchBookCmmtDetail(params)`: 도서 코멘트 상세 정보를 조회합니다.
- `deleteBookCmmt(data)`: 도서 코멘트를 삭제합니다.

### 3. 도서 주문 (Book Order)

- `fetchCourierOrderList(params)`: 택배 주문 목록을 조회합니다.
- `fetchDirectOrderList(params)`: 방문 수령 주문 목록을 조회합니다.
- `fetchOrderRevenueList(params)`: 매출 현황을 조회합니다.
- `updateTrackingNo(data)`: 송장 번호를 등록/수정합니다.
- `fetchOrderDetail(params)`: 주문 상세 내역을 조회합니다.
