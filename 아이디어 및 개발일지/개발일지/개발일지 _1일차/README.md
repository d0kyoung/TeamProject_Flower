# 웹 UI 구성 회의

## 관리자 페이지 UI 구성 회의

- **일시:** 2023.09.20. 16:00
- **장소:** 이룸관 스터디룸 2

### 관리자 페이지

<img src="https://github.com/donggyunhuh/TeamProject_Flower/blob/main/%EA%B0%9C%EB%B0%9C%EC%9D%BC%EC%A7%80%20%EC%82%AC%EC%A7%84/%EA%B4%80%EB%A6%AC%EC%9E%90%20%ED%8E%98%EC%9D%B4%EC%A7%80/%EA%B4%80%EB%A6%AC%EC%9E%90%201.png?raw=true"/>

- 전체적인 관리자 페이지 UI입니다. 꽃 관리, 판매자 관리 탭, 사용자 관리, 거래 모니터링, 주문서 관리, 보안 관리 페이지와 연결됩니다.

### 꽃 관리 페이지

<img src="https://github.com/donggyunhuh/TeamProject_Flower/blob/main/%EA%B0%9C%EB%B0%9C%EC%9D%BC%EC%A7%80%20%EC%82%AC%EC%A7%84/%EA%B4%80%EB%A6%AC%EC%9E%90%20%ED%8E%98%EC%9D%B4%EC%A7%80/%EA%BD%83%20%EA%B4%80%EB%A6%AC%20%ED%8E%98%EC%9D%B4%EC%A7%80.png?raw=true"/>

- 꽃 관리를 할 수 있는 페이지 입니다. 꽃을 선택한 후 꽃에 대한 간단한 설명을 추가/수정/삭제 할 수 있습니다. 위 데이터는 DB와 연동되어 관리자라면 누구나 확인 가능합니다.

### 사용자 관리 페이지

<img src="https://github.com/donggyunhuh/TeamProject_Flower/blob/main/%EA%B0%9C%EB%B0%9C%EC%9D%BC%EC%A7%80%20%EC%82%AC%EC%A7%84/%EA%B4%80%EB%A6%AC%EC%9E%90%20%ED%8E%98%EC%9D%B4%EC%A7%80/%EC%82%AC%EC%9A%A9%EC%9E%90%20%EA%B4%80%EB%A6%AC.png?raw=true"/>

- 암호화된 사용자(회원)의 이름, id, pw, 전화번호를 확인하고 악성 회원인 경우 체크란을 만들어 중점적으로 관리 할 수 있도록 합니다.

### 판매자 관리 페이지

<img src="https://github.com/donggyunhuh/TeamProject_Flower/blob/main/%EA%B0%9C%EB%B0%9C%EC%9D%BC%EC%A7%80%20%EC%82%AC%EC%A7%84/%EA%B4%80%EB%A6%AC%EC%9E%90%20%ED%8E%98%EC%9D%B4%EC%A7%80/%ED%8C%90%EB%A7%A4%EC%9E%90%20%EA%B4%80%EB%A6%AC.png?raw=true"/>

- 매장명, 매장위치, 매장 연락처를 확인할 수 있습니다. 매장사진은 직접 판매자에게 요청하여 업데이트하거나 기본 이미지로 대체합니다. 판매량에 따라 파워셀러 여부를 선택 할 수 있습니다.

### 주문서 관리 페이지

<img src="https://github.com/donggyunhuh/TeamProject_Flower/blob/main/%EA%B0%9C%EB%B0%9C%EC%9D%BC%EC%A7%80%20%EC%82%AC%EC%A7%84/%EA%B4%80%EB%A6%AC%EC%9E%90%20%ED%8E%98%EC%9D%B4%EC%A7%80/%EC%A3%BC%EB%AC%B8%EC%84%9C%20%EA%B4%80%EB%A6%AC.png?raw=true"/>

- 관리자가 주문 목록을 조회하고 주문 상태를 업데이트할 수 있습니다. 중개된 거래의 주문을 관리하고 주문 상태를 업데이트할 수 있는 기능을 포함합니다. 주문 검색 및 필터링 할 수 있습니다.

### 거래 모니터링 페이지

<img src="https://github.com/donggyunhuh/TeamProject_Flower/blob/main/%EA%B0%9C%EB%B0%9C%EC%9D%BC%EC%A7%80%20%EC%82%AC%EC%A7%84/%EA%B4%80%EB%A6%AC%EC%9E%90%20%ED%8E%98%EC%9D%B4%EC%A7%80/%EA%B1%B0%EB%9E%98%EB%AA%A8%EB%8B%88%ED%84%B0%EB%A7%81.png?raw=true"/>

- 고객명, 전화번호, 픽업날짜, 픽업시간, 주소, 주문 내역이 **List**형식으로 확인 할 수 있습니다. DB 데이터와 연결되어 있으며, 파워셀러 선정시 활용되는 자료입니다.

## 깃 설치 및 깃허브 연동

- 각자의 로컬 개발 환경에 깃 설치 후 메인 레포지토리에 각자의 로컬 저장소를 연결했습니다.

- 커밋과정과 소스코드 Run 과정에서 오류가 발생했으나, 오류 발생원인을 확인하고 해결할 수 있었습니다.

**오류 원인** : jdk 설치 버전이 다름, 소스코드 open 폴더 잘못 지정, 스프링부트 설치환경 다름.
--> 깃허브 소스코드 레포지토리 폴더 수정과 jdk 설치버전 jdk-20 버전으로 통일로 해결!

- 각 컴퓨터에서 commit, Pull Request 과정을 성공, 협업 준비가 완료됐습니다.

<img src="https://github.com/donggyunhuh/TeamProject_Flower/blob/main/%EA%B0%9C%EB%B0%9C%EC%9D%BC%EC%A7%80%20%EC%82%AC%EC%A7%84/%EA%B4%80%EB%A6%AC%EC%9E%90%20%ED%8E%98%EC%9D%B4%EC%A7%80/Pull%20request%20%EC%98%88%EC%8B%9C.png?raw=true"/>

## 주문 페이지 UI 구성 회의

### **메인 홈페이지 예상**

  <img src="https://github.com/donggyunhuh/TeamProject_Flower/blob/Donggyun/%EA%B0%9C%EB%B0%9C%EC%9D%BC%EC%A7%80%20%EC%82%AC%EC%A7%84/%EC%A3%BC%EB%AC%B8/%ED%99%88%20%ED%99%94%EB%A9%B4.jpg?raw=true" width="436" height="617"/>

---

### AI 꽃 추천 페이지 예상

<img src="https://github.com/donggyunhuh/TeamProject_Flower/blob/Donggyun/%EA%B0%9C%EB%B0%9C%EC%9D%BC%EC%A7%80%20%EC%82%AC%EC%A7%84/%EC%A3%BC%EB%AC%B8/AI%20%EA%BD%83%20%EC%B6%94%EC%B2%9C.jpg?raw=true" width="436" height="617"/>

---

### AI 꽃 추천 완료 페이지 예상

<img src="https://github.com/donggyunhuh/TeamProject_Flower/blob/Donggyun/%EA%B0%9C%EB%B0%9C%EC%9D%BC%EC%A7%80%20%EC%82%AC%EC%A7%84/%EC%A3%BC%EB%AC%B8/%EA%BD%83%20%EC%B6%94%EC%B2%9C%20AI%20%20%EC%8B%A4%ED%96%89%20%EC%99%84%EB%A3%8C.jpg?raw=true" width="436" height="617"/>

---

### 주문하기 페이지 에상

<img src="https://github.com/donggyunhuh/TeamProject_Flower/blob/Donggyun/%EA%B0%9C%EB%B0%9C%EC%9D%BC%EC%A7%80%20%EC%82%AC%EC%A7%84/%EC%A3%BC%EB%AC%B8/%EC%A3%BC%EB%AC%B8%ED%95%98%EA%B8%B0%20%ED%8E%98%EC%9D%B4%EC%A7%80.jpg?raw=true" width="436" height="617"/>

---

### 주문내역 페이지 예상

<img src="https://github.com/donggyunhuh/TeamProject_Flower/blob/Donggyun/%EA%B0%9C%EB%B0%9C%EC%9D%BC%EC%A7%80%20%EC%82%AC%EC%A7%84/%EC%A3%BC%EB%AC%B8/%EC%A3%BC%EB%AC%B8%EB%82%B4%EC%97%AD.jpg?raw=true" width="436" height="617"/>

---

### 매장 매칭 제안 페이지 예상

<img src="https://github.com/donggyunhuh/TeamProject_Flower/blob/Donggyun/%EA%B0%9C%EB%B0%9C%EC%9D%BC%EC%A7%80%20%EC%82%AC%EC%A7%84/%EC%A3%BC%EB%AC%B8/%EB%A7%A4%EC%9E%A5%20%EC%A0%9C%EC%95%88%20%ED%8E%98%EC%9D%B4%EC%A7%80.jpg?raw=true" width="436" height="617"/>

---
