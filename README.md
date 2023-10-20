# 구현할 기능 목록
- 게임 시작 시 문구 출력
  - 문구 : 숫자 야구 게임을 시작합니다.
- 랜덤으로 숫자 선택
  - 1~9 중 서로 다른 3가지의 숫자여야 한다.
- 사용자로부터 숫자를 입력받기
  - 서로 다른 3자리의 수/1/2 이외의 입력은 throw문을 사용해 예외를 발생시킨후 애플리케이션은 종료시킨다.
- 입력받은 숫자와 랜덤 숫자를 비교하여 볼과 스트라이크 개수 계산
  - 동일한 숫자가 같은 위치에 있는 경우 => 스트라이크
  - 동일한 숫자가 다른 위치에 있는 경우 => 볼
- 계산된 결과 출력
  - 0볼0스트라이크 => 낫싱
  - 3스트라이크 => 3스트라이크 3개의 숫자를 모두 맞히셨습니다! 게임 종료 게임을 새로 시작하려면 1, 종료하려면 2를 입력하세요. 출력
  - 위의 두가지 경우를 제외하면 볼과 스트라이크의 개수 출력
- 게임 진행
  - 3스트라이크가 아닌 경우 => 사용자로부터 숫자를 입력받기 단계로 돌아가 반복
  - 3스트라이크인 경우 => 1을 입력받은 경우 게임 재시작, 2를 입력받은 경우 게임 종료
  
  
