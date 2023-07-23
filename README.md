# HiFive(2023)
구디 아카데미 세미 프로젝트
* 참여인원 : 5명
* 프로젝트 기간 : 5/25~6/29
* 프로젝트 주제 : 중고 거래 사이트
* 프로젝트 개요 : 중고 거래 사이트 이용 시 사용자에 대한 거래 신뢰도가 있고 필요 상품을 검색 시 해당 상품의 시세가 조회되는 사이트를 구현하고자 함
## 담당 역할
✅ 클릭 시 해당 servlet 패키지로 이동합니다.
### 👨‍💻김찬은
* 상품 카테고리
  * [cateory](https://github.com/leebib1/SemiProject_GDJ64/tree/main/semi-hifive/src/main/java/com/semi/category)
  * [productlist](https://github.com/leebib1/SemiProject_GDJ64/tree/main/semi-hifive/src/main/java/com/semi/productlist)
* 상품 시세
  * 구현 x
### 👩‍💻김현영
#### UI 담당 : 전체적인 UI 템플릿 설계 및 구현
#### DB 설계 담당 : 회원 테이블 중심 설계 및 구축, 관리
* 메인 페이지
  * [main](https://github.com/leebib1/SemiProject_GDJ64/tree/main/semi-hifive/src/main/java/com/semi/main)
* 마이 페이지
  * [mypage](https://github.com/leebib1/SemiProject_GDJ64/tree/main/semi-hifive/src/main/java/com/semi/mypage)
### 👩‍💻이은지
#### Git 관리: Github을 통한 형상관리 총괄
#### DB 설계 담당 : 관계형 데이터베이스 설계 및 구축, 관리
* 고객센터
  * [service(고객센터)](https://github.com/leebib1/SemiProject_GDJ64/tree/main/semi-hifive/src/main/java/com/semi/sc/board/controller)
* 신고하기
  * [service(거래 내역 신고)](https://github.com/leebib1/SemiProject_GDJ64/tree/main/semi-hifive/src/main/java/com/semi/sc/inquiry/controller)
  * [service(판매글 신고)](https://github.com/leebib1/SemiProject_GDJ64/tree/main/semi-hifive/src/main/java/com/semi/sc/report/controller)
### 👨‍💻최주영
#### 팀장
* 로그인 및 회원가입
  * [member](https://github.com/leebib1/SemiProject_GDJ64/tree/main/semi-hifive/src/main/java/com/semi/member)
* 상품 등록
  * [productregist](https://github.com/leebib1/SemiProject_GDJ64/tree/main/semi-hifive/src/main/java/com/semi/productregist)
### 👨‍💻허성현
#### UI 담당 : header, footer, 이벤트 베너 이미지 담당
품 테이블 중심 설계 및 구축, 관리
* 상품 상세 페이지
  * [productpage](https://github.com/leebib1/SemiProject_GDJ64/tree/main/semi-hifive/src/main/java/com/semi/productpage)
* 상품 검색
  * [search](https://github.com/leebib1/SemiProject_GDJ64/tree/main/semi-hifive/src/main/java/com/semi/search)
## 개발 환경
### FRONT-END
![FNTool](https://github.com/leebib1/SemiProject_GDJ64/assets/128957257/c1fb4ad1-9ac4-46b5-8509-d89360268fd6)
### BACK-END
![BETool](https://github.com/leebib1/SemiProject_GDJ64/assets/128957257/32d9f5f6-b55e-4316-88a7-537d754a5758)
### TOOLS
![Tools](https://github.com/leebib1/SemiProject_GDJ64/assets/128957257/939e1151-2809-4638-b37a-4407b4fee9cb)
### ETC
![ETC](https://github.com/leebib1/SemiProject_GDJ64/assets/128957257/78cc4589-38f4-48a2-a8d2-67a1450ee3d3)

## 프로젝트 진행 방식
### 회의
프로젝트 진행 시작 전 주제 구상, UI 설계, 논리 DB 설계를 위해 매주 목요일 회의를 진행.
팀 구글 계정을 만들어서 노션에 연동 후 간단하게 회의록을 기록.
![회의기록](https://github.com/leebib1/SemiProject_GDJ64/assets/128957257/779d08e7-5748-4ebe-8dc5-ae2d31f774d3)
### Git
1. 개인 브런치를 이용해 개인 로컬 레포지토리에서 미완성인 코드도 자유롭게 commit 가능
2. 기능 완성 시 메인 브런치 pull -> 충돌 해결(없을 시 패스) -> 로컬 레포지토리의 최신 버전 push
3. DB 접속 정보 설정 xml 파일, SQL문 작성된 xml 파일, upload 폴더 등은 개인적으로 주고 받으며 Git 관리에서 제외
