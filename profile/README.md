## 📖 태극 항공 프로젝트 Taeguk

![image](https://github.com/Final-Project-Team-2/Taegukair/assets/156178513/4e45c976-46a4-45d6-947b-7b714c1fba1d)

배포 URL : https://taegukair.site
Test ID : admin
Test PW : 1234

<br>

## 프로젝트 소개

태극항공 프로젝트는 대한항공 웹사이트를 레퍼런스 기반 개발하여 국내 이동만 가능하도록 기능을 축소 및 재구성한 웹 애플리케이션입니다. Spring Boot와 JPA를 백엔드에서 사용하여 강력하고 유연한 서버를 구축하였고, React를 프론트엔드에 연동하여 사용자 친화적인 UI를 제공했습니다.

<br>

## 팀원 구성
| **오현성** | **권웅진** | **이총제** |
| :------: |  :------: | :------: |

<br>

## 1. 개발 환경

-Front : <img src="https://img.shields.io/badge/HTML-fe5656?style=for-the-badge&logo=HTML&logoColor=red">, <img src="https://img.shields.io/badge/React-3776AB?style=for-the-badge&logo=React&logoColor=red">

-Back-end : <img src="https://img.shields.io/badge/SpringBoot-74d56a?style=for-the-badge&logo=SpringBoot&logoColor=red"> <img src="https://img.shields.io/badge/JPA-a667cf?style=for-the-badge&logo=JPA&logoColor=red">

-DB : <img src="https://img.shields.io/badge/MySQL-49bcd7?style=for-the-badge&logo=MySQL&logoColor=red">

-버전 및 이슈관리 : <img src="https://img.shields.io/badge/Github-49ba01?style=for-the-badge&logo=Github&logoColor=red">

-협업 툴 : <img src="https://img.shields.io/badge/Discord-dec7f1?style=for-the-badge&logo=Discord&logoColor=red"> <img src="https://img.shields.io/badge/Notion-cbf3de?style=for-the-badge&logo=Notion&logoColor=red"> 

-서비스 배포 환경 : <img src="https://img.shields.io/badge/AWS-ffff2b?style=for-the-badge&logo=AWS&logoColor=black">

-디자인 : <img src="https://img.shields.io/badge/Figma-fa3303?style=for-the-badge&logo=Figma&logoColor=white">

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=leechongjae&layout=compact)](https://github.com/leechongjae/github-readme-stats)


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

![image](https://github.com/Final-Project-Team-2/Taegukair/assets/156178513/6b13ee0d-05c6-47b7-8538-d17f1485cb89)   ![image](https://github.com/Final-Project-Team-2/Taegukair/assets/156178513/fef0992f-6f4c-44d8-9f37-9d945a4e597e)

<br>

## 4. 역할 분담

### 🍊권웅진
**기능**
    예약, 항공편, 항공기 관리
    
### 👻오현성
**기능**
    고객의 말씀, 예약, 공항 관리

### 🐬이총제
**기능**
    로그인, 로그아웃, 마이페이지, 회원가입
    
<br>

## 5. 개발 기간 및 작업 관리

### 개발 기간

전체 개발 기간 : 2024-05-14 ~ 2024-06-14


[노션 바로가기!](https://www.notion.so/ohgiraffers/7621f33977904cce9e3c83893113e929)

<br>

### 작업 관리

GitHub Projects와 Issues를 사용하여 진행 상황을 공유했습니다.
주간회의를 진행하며 작업 순서와 방향성에 대한 고민을 나누고 notion에 회의 내용을 기록했습니다.

<br>

## 8. 프로젝트 후기

### 🍊권웅진

### 👻오현성
이번 프로젝트를 시작하면서, 팀원들과 충분한 소통을 통해 일정을 정하고 프로젝트를 진행하면 큰 이슈 없이 마무리할 수 있을 것이라고 생각했습니다. 그러나 실제로 진행하면서 예상치 못한 다양한 이슈들이 발생하며 일정 수립의 중요성을 다시 한번 느낄 수 있었습니다.
이번 프로젝트를 통해 일정 수립의 중요성을 다시 한번 느끼게 되었으며, 리액트와 스프링부트를 활용한 개발 경험을 쌓을 수 있었습니다. 여러 이슈에도 불구하고 팀원들과 협력하여 문제를 해결해 나가면서 많은 것을 배울 수 있었고, 이는 앞으로의 프로젝트에도 큰 도움이 될 것이라고 생각했습니다. 앞으로 진행하게될 프로젝트에서는 일정 수립과 팀원 간의 소통을 더욱 강화하여 더욱 성공적인 프로젝트를 진행할 수 있도록 노력하겠습니다.

### 🐬이총제
이번 프로젝트를 진행하면서 여러 사건 사고가 있었지만, 정해진 시간 안에 끝내야 한다는 부담감 속에서도 중요한 교훈을 얻을 수 있었습니다. 그 중 하나는 시간 관리의 중요성이었습니다. 프로젝트의 마감 기한을 맞추기 위해 효율적으로 작업을 분배하고, 계획을 철저히 세우는 것이 얼마나 중요한지 깨닫게 되었습니다.
또한, 팀원들과의 소통을 통해 많은 것을 배울 수 있었습니다. 협업을 하면서 다양한 의견을 듣고 조율하는 과정에서, 서로의 강점을 활용하고 부족한 부분을 보완하는 법을 익혔습니다. 이러한 경험은 단순히 기술적인 성장뿐만 아니라, 소프트 스킬을 향상시키는 데도 큰 도움이 되었습니다.
이 프로젝트를 통해 얻은 자신감과 기대감은 앞으로의 프로젝트에 큰 밑거름이 될 것입니다. 이번 경험을 바탕으로 더 나은 결과물을 만들어낼 수 있을 것이라는 확신이 들며, 다음 프로젝트에서는 더 효율적이고 능숙하게 작업을 수행할 수 있을 것이라고 기대합니다.
프로젝트를 성공적으로 마무리할 수 있도록 도와준 팀원들과의 협업은 매우 소중한 경험이었고, 이러한 경험들이 모여 저를 더 나은 개발자로 성장하게 할 것입니다.

