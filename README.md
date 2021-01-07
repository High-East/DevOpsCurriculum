# Knowre DevOps Curriculum 2021 (Beta)

## 소개

* Knowre의 신입 데브옵스 엔지니어 교육을 위한 데브옵스 교육 커리큘럼의 2021년 버전입니다.
* 이 커리큘럼을 통해 신입 엔지니어들은 데브옵스의 기본 개념, 리눅스, 네트워크, 형상관리, 컨테이너, 로드밸런싱, CI/CD, AWS, CDN, 자동화 된 테스트, 보안, 마이크로서비스, 모노리포, 로깅과 모니터링, 스트레스 테스트 등의 주제에 관하여 익히게 됩니다.

## 목차
<details><summary>펼치기</summary>
  <p>

  * [Quest 00. 데브옵스란 무엇인가](./Quest00)
  * [Quest 01. 리눅스와 친해지기](./Quest01)
  * [Quest 02. 프로그래밍의 기초](./Quest02)
  * [Quest 03. 네트워크의 기초](./Quest03)
  * [Quest 04. 나의 첫 웹 서비스](./Quest04)
  * [Quest 05. 형상관리툴](./Quest05)
  * [Quest 06. 컨테이너](./Quest06)
  * [Quest 07. 여러 대의 서버로 서비스 하기](./Quest07)
  * [Quest 08. 배포 자동화 하기](./Quest08)
  * [Quest 09. 정적인 컨텐츠 서비스 하기](./Quest09)
  * [Quest 10. 자동화된 테스트](./Quest10)
  * [Quest 11. 보안의 기초](./Quest11)
  * [Quest 12. 마이크로서비스와 람다](./Quest12)
  * [Quest 13. 코드로 인프라 관리하기](./Quest13)
  * [Quest 14. 모노리포와 린팅](./Quest14)
  * [Quest 15. 배포 파이프라인](./Quest15)
  * [Quest 16. 서비스의 운영 (1): 서버 들여다 보기](./Quest16)
  * [Quest 17. 서비스의 운영 (2): 로깅과 모니터링](./Quest17)
  * [Quest 18. 스트레스 테스트](./Quest18)

  </p>
</details>

## 설명

* Quest 0부터 순서대로 각각의 주제들에 관한 퀘스트를 수행하시면 됩니다.
* Knowre의 신입 엔지니어인 경우에는 퀘스트 수행에 필요한 격리된 AWS 계정을 제공합니다. 해당 계정을 자유롭게 쓰되, 부주의로 과도한 비용이 청구되지 않도록 주의하세요!
* 퀘스트 수행에 필요한 리포지토리가 추후 필요해 질때는 각자의 리포지토리를 사용하시면 됩니다.
* 비밀번호나 토큰 스트링 등의 민감한 정보를 공개된 저장소에 커밋하지 않도록 주의하시기 바랍니다.
* 퀘스트는 다음과 같이 구성되어 있습니다(그러나 모든 퀘스트가 다음의 구성요소들을 모두 가지고 있는 것은 아닙니다).
  * Introduction: 소개 페이지입니다.
  * Topics: 이번 퀘스트를 통해 익힐 수 있는 기술이 무엇인지를 나타냅니다.
  * Resources: 토픽을 익히기 위해 참고하면 좋을 링크들입니다.
  * Checklist: Topic들을 제대로 공부했는지를 자문자답 할 수 있는 문항들로 이루어져 있습니다.
  * Quest: 퀘스트를 통해 만들어내야 하는 결과물들을 담고 있습니다.
  * Skeleton: 퀘스트 수행을 위한 스켈레톤 코드입니다.


## 제출

* 제출은 크게 Checklist의 질문에 대한 대답과 Quest의 수행으로 나누어 집니다.
* Checklist의 질문에 대한 대답은 이 저장소를 fork하여 자신의 저장소를 만들고, 그 저장소에 해당 내용을 푸시합니다.
* Quest에서 요구하는 결과물이
  1. 코드인 경우: 개인 계정에 다른 저장소를 만들어 제출합니다
  1. AWS상의 인프라인 경우: 해당 인프라의 위치와 설명을 슬랙으로 제출합니다


### 막혔다면...

* 되도록 검색 등을 통해 스스로 해결해 나가는 것을 권장합니다. 국내 검색엔진의 검색 보다는 구글 검색을 권장합니다.
* 어떠한 알 수 없는 현상이 있어 막혔을 경우 그 현상이 일어나는 최소단위의 코드를 만들다 보면 해결되는 경우가 많습니다.
* 만일 만 하루 이상의 시행착오로 인해 진행이 멈췄을 경우, 제 자리로 찾아 오시면 해결을 보장해 드립니다.
