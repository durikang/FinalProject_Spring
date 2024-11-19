# FinalProject: 의류 쇼핑몰 및 재무 분석 플랫폼

## 프로젝트 목표
1. **판매 실적 및 회사 재무 관리 시각화**
   - 파이썬을 사용하여 데이터 분석 및 시각화 (Pandas, Numpy, Matplotlib, Plotly 등 활용).
   - 선형회귀를 사용하여 예측 분석 포함.

2. **시각화 자료의 저장 및 공유 기능**
   - 시각화 이미지를 ZIP 파일로 다운로드.
   - 시각화 데이터를 엑셀 형식으로 저장.

3. **대용량 데이터 처리**
   - 파이썬으로 대용량 데이터(엑셀 자료)를 Oracle DB에 업로드.

---

## 프로젝트 주제: 의류 쇼핑몰

### 구성 요소
#### 사용자 사이트
1. **화면 구성**
   - **메인 화면**: 상품 목록 및 검색 기능.
   - **로그인 뷰**: 사용자 구분(admin, customer).
   - **상품 상세 페이지**: 상품 정보 및 이미지 표시.
   - **구매 페이지**: 상품 구매 및 결제 기능.

#### 관리자 페이지
1. **접근 제한**
   - 관리자(admin) 계정만 접근 가능.

2. **대시보드**
   - 판매 실적, 재무 관리, 주문 현황 등의 시각화 자료 표시.

3. **관리 기능**
   - **상품 관리**: 상품 등록, 수정, 삭제.
   - **회원 관리**: 회원 정보 조회, 수정, 삭제.
   - **주문 관리**: 주문 상태 조회 및 관리.
   - **판매 관리**: 판매 기록 조회 및 분석.
   - **재무 관리**: 재무 데이터 조회 및 분석.

---

## 세부 요구 사항
### 데이터 관리
1. **시각화 자료**
   - 데이터베이스에서 데이터를 가져와 분석 및 시각화.
   - 시각화 자료를 엑셀 파일로 저장 가능.
   - 관리자 대시보드에서 ZIP 파일로 이미지 다운로드 가능.

2. **데이터 분석 및 업로드**
   - 엑셀 자료를 파이썬(Pandas, Numpy 등)을 사용하여 Oracle DB에 업로드.
   - Java 대신 Python을 사용하여 대용량 데이터 업로드 속도 개선.

---

## 기술 구성
1. **프론트엔드**
   - HTML, CSS, JavaScript.
   - Bootstrap 또는 Tailwind CSS.

2. **백엔드**
   - Spring 또는 Spring Boot (선택 필요).
   - RESTful API 설계.

3. **데이터베이스**
   - Oracle DB.
   - 5년 치 데이터 준비.

4. **데이터 분석 및 시각화**
   - Python (Pandas, Numpy, Matplotlib, Plotly 등).
   - 선형회귀 모델을 사용한 예측 분석.

---

## 추가 구현 사항
1. **파일 저장**
   - 시각화 자료를 ZIP으로 다운로드.
   - 엑셀 자료를 테이블 형태로 저장 가능.

2. **웹페이지 구현**
   - 로그인, 상품 조회, 구매 기능.

3. **협업 체크포인트**
   - 데이터베이스 설계 및 구축.
   - Spring과 Spring Boot 중 백엔드 기술 선택.
   - 5년 치 데이터 확보 및 정리.

---

## 참고 자료
- [JAVA Spring에서 Python 실행하기 - ProcessBuilder 활용](https://velog.io/@jinnnii/JAVA-Spring-%EC%97%90%EC%84%9C-Python-%EC%8B%A4%ED%96%89%ED%95%98%EA%B8%B0-ProcessBuilder)

---

## 다음 단계
1. **웹 구현 계획**
   - Spring 또는 Spring Boot 결정.
   - 각 화면 설계 초안 작성.

2. **데이터 준비**
   - Oracle DB 스키마 설계.
   - 5년 치 데이터 수집 및 정리.

3. **분석 및 시각화 설계**
   - Python 분석 코드 및 시각화 방식 설계.
   - 선형회귀 모델 구체화.

4. **협업 계획**
   - 조원 역할 분담 및 진행도 체크.
