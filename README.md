## WoowaCourse-Precourse-Week2

#### 메인 기능
- n대 자동차의 이름을 쉼표 기준으로 입력 받음 (5자 이하)
- 자동차의 이동 횟수를 입력 받음
- 0~9 사이 무작위 값으로 4 이상이 나올 경우 전진
- 자동차 경주가 끝난 후 우승자를 출력 (공동 우승자는 쉼표로 구분)
- 사용자가 잘못된 값을 입력할 경우 "[ERROR]"로 시작하는 메시지와 함께 Error를 발생시킨 후 종료

#### 에러 메시지
- 자동차 이름을 입력받을 때 이름이 5자를 초과하거나 쉼표로 구분하지 않았을 경우 -> "[ERROR] 자동차 이름은 쉼표(,)로 구분하고, 각각 5자 이하로 입력해야 합니다."
- 자동차의 이동 횟수를 입력 받을 때 숫자가 아닌 문자를 입력한 경우 -> "[ERROR] 이동 횟수는 숫자로만 입력할 수 있습니다."