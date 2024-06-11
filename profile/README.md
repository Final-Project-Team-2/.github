## 📖 태극 항공 홈페이지 Taeguk
<div align="center">

![image](https://github.com/Final-Project-Team-2/Taegukair/assets/156178513/4e45c976-46a4-45d6-947b-7b714c1fba1d)

배포 URL : https://taegukair.site
Test ID : admin
Test PW : 1234

<br>

## 프로젝트 소개

태극 항공은 기차나 버스처럼 간편하게 국내를 빠르고 간편하게 이동하고 싶다는 마음으로 제작했습니다!
국내만 이동하기에 간단하게 이용할 수 있도록 하는것에 포커를 맞추었습니다!
간편한 만큼 합리적인 가격을 받아서 만족도가 업 되도록!!
협력 업체를 이용하게 된다면 더욱 가성비가 높아지는 페이지!


## 팀원 구성
| **오현성** | **권웅진** | **윤시현** | **이총제** |
| :------: |  :------: | :------: | :------: |

## 1. 개발 환경

-Front : <img src="https://img.shields.io/badge/HTML-fe5656?style=for-the-badge&logo=HTML&logoColor=red">, <img src="https://img.shields.io/badge/React-3776AB?style=for-the-badge&logo=React&logoColor=red">

-Back-end : <img src="https://img.shields.io/badge/SpringBoot-74d56a?style=for-the-badge&logo=SpringBoot&logoColor=red"> <img src="https://img.shields.io/badge/JPA-a667cf?style=for-the-badge&logo=JPA&logoColor=red">

-DB : <img src="https://img.shields.io/badge/MySQL-49bcd7?style=for-the-badge&logo=MySQL&logoColor=red">

-버전 및 이슈관리 : <img src="https://img.shields.io/badge/Github-49ba01?style=for-the-badge&logo=Github&logoColor=red">

-협업 툴 : <img src="https://img.shields.io/badge/Discord-dec7f1?style=for-the-badge&logo=Discord&logoColor=red"> <img src="https://img.shields.io/badge/Notion-cbf3de?style=for-the-badge&logo=Notion&logoColor=red"> 

-서비스 배포 환경 : <img src="https://img.shields.io/badge/AWS-ffff2b?style=for-the-badge&logo=AWS&logoColor=black">

-디자인 : <img src="https://img.shields.io/badge/Figma-fa3303?style=for-the-badge&logo=Figma&logoColor=white">

<br>

## 2. 채택한 개발 기술과 브랜치 전략

### React, styled-component

React
    컴포넌트화를 통해 추후 유지보수와 재사용성을 고려했습니다.
    유저 배너, 상단과 하단 배너 등 중복되어 사용되는 부분이 많아 컴포넌트화를 통해 리소스 절약이 가능했습니다.
    props를 이용한 조건부 스타일링을 활용하여 상황에 알맞은 스타일을 적용시킬 수 있었습니다.
    빌드될 때 고유한 클래스 이름이 부여되어 네이밍 컨벤션을 정하는 비용을 절약할 수 있었습니다.
    S dot naming을 통해 일반 컴포넌트와 스타일드 컴포넌트를 쉽게 구별하도록 했습니다.
    

Redux
    Redux는 애플리케이션의 상태를 중앙에서 관리하여 유지보수와 확장성을 고려했습니다.
    중앙 집중화된 상태 관리 덕분에 여러 컴포넌트에서 공통적으로 사용되는 상태를 쉽게 공유하고 업데이트할 수 있었습니다.
    액션과 리듀서를 이용해 상태 변화를 예측 가능하게 만들었으며, 이를 통해 디버깅과 상태 추적이 용이해졌습니다.
    미들웨어를 사용하여 비동기 작업을 처리하고, 복잡한 비즈니스 로직을 분리해 코드의 가독성을 높였습니다.
    React와 함께 사용하여 컴포넌트 기반의 구조에서도 일관성 있는 상태 관리를 유지할 수 있었습니다.
    Redux DevTools를 통해 상태 변화를 시각적으로 확인하고, 타임 트래블 디버깅을 활용해 효율적인 디버깅이 가능했습니다.

### 브랜치 전략

Git-flow 전략을 기반으로 main, develop 브랜치와 feature 보조 브랜치를 운용했습니다.
master와 기능별 브랜치로 나누어 개발을 하였습니다.
    **master** 브랜치는 개발 완료 단계에서만 사용하는 브랜치입니다.
    **기능** 브랜치는 개발 단계에서 협업을 하며 팀원들과의 충돌을 줄여서 이슈를 줄이기 위해 나누었습니다. 

<br>

## 3. 프로젝트 구조

react 및 springboot 설계도 올리기

## 4. 역할 분담

### 🍊권웅진
**기능**
    예약, 항공편, 항공기 관리
### 👻오현성
**기능**
    고객의 말씀, 예약, 공항 관리
### 😎윤시현

### 🐬이총제
**기능**
    로그인, 로그아웃, 마이페이지, 회원가입
    
<br>

## 5. 개발 기간 및 작업 관리

### 개발 기간

전체 개발 기간 : 2024-05-14 ~ 2024-06-14
  노션 페이지 넣기


### 작업 관리

GitHub Projects와 Issues를 사용하여 진행 상황을 공유했습니다.
주간회의를 진행하며 작업 순서와 방향성에 대한 고민을 나누고 notion에 회의 내용을 기록했습니다.


## 6. 신경 쓴 부분

없어도 무관하나 어필할 수 있는 공간으로 생성


## 7. 페이지별 기능

기능 이미지 또는 발표 자료 준비하는 느낌으로 이미지 또는 설명으로 부각시키기

## 8. 프로젝트 후기

### 🍊권웅진

### 👻오현성

### 😎윤시현

### 🐬이총제
프로젝트를 마무리하며 후기 작성

</div>
