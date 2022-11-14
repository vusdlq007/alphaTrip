


# AlphaTrip Service (v0.0.1)
* * *
### AlphaTrip 서비스 개발 저장소.

기간 : 2022. 11. 18(금) ~ 2023. 01. 31(화)

파트 : 김윤권 (FullStack,DB,DevOps),
      김동우 (FullStack,DB)

Confluence 주소 : https://alphatrip.atlassian.net/wiki/spaces/A/pages/229417/Alpha+Trip

Jira 주소 : https://alphatrip.atlassian.net/jira/software/projects/AL/boards/1

##[주요 서비스 API]

* **[통합 서비스 제공 API]** : Core-Api
* **[인증 API]** : Auth-Api
* **[회원 관리 API]** : User-Api
* **[장소 서비스 API]** : Place-Search-Api
* **[추천 서비스 API]** : Recommend-Api

### 각 API 프로젝트 공통 스펙
- 언어 / 버전 : java / 11
- 프레임워크 : Spring boot 2.7.4
- RDBMS : Mariadb 10.4 (docker container)
- Swagger 2.0 적용
  (각 API의 application.yml에 상세 접근 주소 정리하였습니다.)

## 설계 내용
###[공통]





* * *
####[첨부 파일 목록 및 설명]
- apTrip_schema.sql : DB 스키마
- apTip_Member_erd.pdf : DB ERD
