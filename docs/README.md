### 기능 목록
---
- 당첨 번호를 입력 받는다.
  - 쉼표로 구분하고, 숫자의 범위는 1부터 45까지 이다.
  - 서로 다른 6개의 임의의 수여야 한다.

- 보너스 번호를 입력 받는다.
  - 1부터 45까지의 숫자 중 1개 입력 받는다.

- 로또 구입 금액을 입력 받는다.
  - 1000원 단위이며, 1000원으로 나누어 떨어지지 않으면 예외처리 한다.
  - 한 장당 1부터 45까지 서로 다른 6개의 임의의 수를 생성한다.

- 사용자가 구매한 로또 수량과 로또 번호를 출력한다.
  - 로또 번호는 오름차순으로 정렬한다.

- 당첨 내역을 출력한다.

- 사용자가 구입한 로또 금액과 당첨 금액으로 수익률을 확인할 수 있다.
  - 수익률은 소수점 둘째 자리에서 반올림한다. 

---
### 예외 처리
- `IllegalArgumentException`를 발생시키고, "[ERROR]" 로 시작하는 에러 메세지를 출력한 후 그 부분부터 입력을 다시 받는다.
  - `Exception`이 아닌 `IllegalArgumentException`, `IllegalStateException` 등과 같은 명확한 유형을 처리한다.