![ColorsBanner](README-asset/colors-banner.png)

<br>

## 목차
[1. 프로젝트 개요](#1-프로젝트-개요)
- [프로젝트 목표](#1-프로젝트-목표)
- [전체 일정](#2-전체-일정)
- [구성원](#3-구성원)


[2. 프로젝트 설계](#2-프로젝트-설계)
- [Figma](#1-figma)
- [ERD](#2-erd-link)
- [아키텍처](#3-아키텍처)
- [REST API](#4-rest-api-link)

[3. 프로젝트 파일 구조](#3-프로젝트-파일-구조)


[4. 프로젝트 산출물](#4-프로젝트-산출물)

<br>

## 1. 프로젝트 개요
  ### 1) 프로젝트 목표
    다양한 사람들과 함께 소통하며 개인의 얼굴, 분위기와 어울리는 색상을 찾을 수 있는 서비스 개발
  ### 2) 전체 일정
  | 기 간 | 내 용 |
  | :---: | :---: |
  | 2022. 07. 05. ~ 2022. 07. 19. | 아이디어 선정 및 사용자 요구사항 분석 |
  | 2022. 07. 15. ~ 2022. 07. 27. | 요구사항 정의서 작성, Mock-up / ERD / REST API 설계 |
  | 2022. 07. 25. ~ 2022. 07. 29. | 회원가입, 로그인 등 기본 서비스 개발 |
  | 2022. 07. 30. ~ 2022. 07. 15. | OpenVidu를 이용한 화상 미팅 서비스 개발 / Face-Detection 적용 / Rest API 서버 개발 |
  | 2022. 08. 16. ~ 2022. 08. 19. | 서비스 배포 및 유지보수 |
  ### 3) 구성원
  SSAFY 대전캠퍼스 7th B208
  |   Name(Git)   | [송다경](https://github.com/sa11k/) | 김민영 | [김찬일](https://github.com/chanilkim) | 이한기 | [강민성](https://github.com/pfcskms1997) | [오정환](https://github.com/Ojeonghwan) |
  | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
  | Position | :crown: / Frontend | Frontend | Frontend | Frontend | Backend | Backend |

## 2. 프로젝트 설계
   ### 1) Figma
   https://www.figma.com/file/0pfzHeX6s46qoyzQOuOdr2/%EA%B9%94%EB%A7%9E%EC%B6%A4?node-id=226%3A767
   ### 2) ERD [(link)](README-asset/erd.png)
   ### 3) 아키텍처
   ![architecture](README-asset/architecture.png)
   ### 4) REST API [(link)](README-asset/rest-api-docs.pdf)
     

## 3. 프로젝트 파일 구조
 >  Frontend
```
colors
├── build
├── node_modules
├── public
└── src
    ├── api
    ├── assets
    │   ├── font
    │   ├── imagedefault
    │   ├── models
    │   ├── mypage
    │   └── videos
    ├── components
    │   ├── common
    │   ├── EnterancePage
    │   ├── main
    │   ├── myPage
    │   ├── topic
    │   ├── user
    │   ├── videochat
    │   │   └── colorPallete
    │   └── Voting
    ├── router
    ├── store
    │   └── modules
    └── views
        ├── MeetingView
        └── VotingView
```



> Backend
```
└── colors
      ├── config
      ├── controller
      ├── database
      |     ├── entity
      |     └── repository
      ├── enumdata
      ├── interceptor
      ├── request
      ├── response
      ├── service
      └── util
```

## 4. 프로젝트 산출물
  - [발표자료](exec/발표자료.pptx)
  - [UCC](http://www.youtube.com)
  - [포팅 매뉴얼](exec/포팅매뉴얼.pdf)
