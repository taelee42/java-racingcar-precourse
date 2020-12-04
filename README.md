## 🦊 구현할 기능 목록

#### 사용자에게 게임 정보 입력 받기

- [입출력] 경주할 자동차 입력 받기
- [출력] "경주할 자동차 이름을 입력하세요.(이름은 쉼표(,) 기준으로 구분)"
  - [입력] ','로 구분된 차 목록 입력받기
  - [예외처리] 입력을 ','로 나눴을 때 각각의 이름이 글자가 없거나 5글자 초과인 경우 
  - 예외  문구는 [ERROR]로 시작, 예) ""[ERROR] 시도 횟수는 숫자여야 한다."
- [입출력] 게임 차수 입력받기
- [출력] "시도할 회수는 몇회인가요?"
  - [예외] 1 이상의 정수가 아닌 경우 

#### 내부 연산

- 경주할 자동차 입력을 '**,**' 기준으로 배열에 나눠서 저장
- 매 라운드, 경주 차마다 0~9사이의 랜덤넘버로 전진할지(4이상) 멈출지(3이하) 결정
- 라운드마다 경주차의 위치를 기록
- 최종 라운드를 마치고 우승자를 계산

#### 실행결과 출력

- [출력]매 라운드마다 경주차의 위치를 '**-**'로 표현
- [출력]최종 라운드의 경우 우승자 출력




