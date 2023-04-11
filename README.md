# jwp-racingcar

자동차 경주 미션 저장소

## 프로그램 정의

사용자가 자동차 목록과 시도 횟수를 입력하면 우승자를 가리는 프로그램

## 구현 기능 목록
- [x] 자동차 목록을 입력 받는다.
- [x] 시도 회수를 입력 받는다.
- [x] 자동차를 생성한다
- [x] 입력값을 기준으로 자동차 목록을 생성한다.
- [x] 자동차 이동 여부를 판단한다.
- [x] 자동차를 움직이게 한다.
- [x] 최종 우승자를 판단한다.
- [x] 최종 우승자를 출력한다.
- [x] 자동차의 현재 위치를 출력한다.
- [x] 움직임을 판단하는 숫자를 생성한다.

## 인풋 구현
- [x] 참여하는 자동차의 이름을 ","로 구분하여 입력한다
- [x] 게임의 총 진행 회수를 입력한다

## 아웃풋 구현
- [x] 모든 게임이 종료된 후 최종 위치가 가장 많은 자동차를 우승자로 선정하여 출력한다. 이 때 우승자는 다수일 수 있다.

## 검증 처리
- [x] 자동차 이름은 1~5자 이내로 입력해야 한다
- [x] 시도 횟수는 상한선이 없지만 0을 입력할 수 없다

## 객체 역할 정의

- Car
    - [x] 스스로 움직일 수 있다
    - [x] 본인의 위치를 알 수 있다
    - [x] 움직여도 되는 상황인지를 판단할 수 있다
- Controller
  - "api"
    - GET :
      - [x] RESPONSE : index 페이지를 보여준다
  - "api/plays"
    - POST : 
      - [ ] REQUEST : 차량의 이름과 시도횟수를 전송한다
      - [ ] RESPONSE : 우승자와 각 차량의 이름 및 위치를 출력한다
