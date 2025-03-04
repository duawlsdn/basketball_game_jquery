## 🏀 Basketball Game Project

### Project 소개

- 컴퓨터와 사용자의 간에 번갈아 가며 슛을 하고 득점이 높은 쪽이 이기는 간단한 게임입니다.
- 초기 버전은 Vanilla JavaScript로 구현했으며,
- 2번의 리팩토링 중 첫번째는 객체화, 함수화를 통해 로직을 좀더 생산성 있게 정리하였습니다.
- 두 번째는 Jquery를 도입하여 DOM 조작 및 이벤트 처리 방식을 간결화 했습니다.

### Project 히스토리

#### 1. 초기버전( Vanilla JavaScript)
- DOM 조작 :  getElementById(), getElementByClassName()을 활용
- 이번트 처리 : onclick 속성을 사용, 버튼 클릭 이벤트 처리
- 전역 변수 사용 : userScore, comScore, shootType 등으로 게임 상태 관리
- 로직 구현 : 순차적인 절차 지향 프로그래밍 방식으로 작성

#### 2. 리팩토링
- 코드 중복 제거 : 점수 업데이트, 버튼 활성화/비활성화 의 기능을 함수화
- 객체화 : game, computer, user 객체를 도입하여 각각의 관련 변수를 하나의 객체로 묶음
  - computer 객체 내에 scroe,percent2,percent3 속성을 대입하여 각각의 comScore, comPercent2, comPercent3 를 리팩토링
  

