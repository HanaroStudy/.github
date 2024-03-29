# HanaroStudy

## 목표

>프레임워크가 제공하는 기능을 직접 구현해보면서 내부 동작을 깊이있게 이해한다.  
금융권 비즈니스 프로세스를 이해하고 그 과정에서 어떤 요구사항을 고려할 수 있는지 고민한다.  
금융권 비즈니스 프로세스를 자바로 구현한다.  
작은 기능부터 점진적 확장을 통해 하나의 웹 서비스를 구현한다.

#### 진행 방법
##### 공통 사항
- 주차 별 미션을 각자의 로컬환경에서 일주일간 구현.
- 주 1회 오프라인 미팅을 통해 서로의 구현 과정을 공유.
- 서로의 코드 리뷰 및 피드백을 진행한다.
##### 깃 브랜칭
- 스터디 레포지토리를 fork하여 각자의 레포지토리의 환경에서 진행한다.
- 주차별 브랜치(Ex. week1)를 만들어 해당 브랜치에서 해당 주차의 작업을 진행한다.
- 작업은 기능 단위의 커밋을 통해 스터디원이 쉬운 리뷰를 할 수 있도록 한다.
- 해당 주차의 스터디가 끝나면 자신의 레포지토리의 main 브랜치에 PR을 보낸다.
- 스터디원의 리뷰이후 PR을 main에 merging한다.
- 각 주차별 2 ~ 5 단계를 반복한다.

### 주차 별 구현 목표
#### - 3.11 ~ 3.17 (1주)
- 클라이언트가 서버의 URL에 요청을 보내면 우리의 서버는 어떤 일을 하는가?
- HTTP 통신이란 ?
- HTTP 요청 수신 및 응답 구현
***
#### - 3.18 ~ 3.31 (2주 ~ 3주)
- 금융권 비즈니스 프로세스 분석(계좌 개설, 계좌 이체, 입금, 출금, 잔액 조회)
- 도메인 정의 및 비즈니스 로직 구현
- 예외 핸들링
***
#### - 3.31 ~ 4.7 (4주)
- 1주차에 구현했던 앞단(Controller)의 로직과 비즈니스 로직을 연결
- 확장성있는 설계로 리팩터링 (새로운 기능이 추가된다고 가정했을 때, 기존의 코드를 수정할 필요가 없어야 한다.)
***
#### - 4.8 ~ 4.21(5주 ~ 6주)
- 동시성이란 ?
- 동시성 이슈 해결 전략은 ?
- 동시성 이슈를 고려하여 설계 리팩터링
- 동시성 이슈 테스트 코드 작성
***
