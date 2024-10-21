# java-calculator-precourse

## 구현하는 기능
1. **문자열 입력 처리 기능**
   - 사용자에게 '덧셈할 문자열을 입력해 주세요.' 라는 알람문을 띄어 문자열을 입력 받는 기능이다.
2. **입력받은 문자열 처리 기능**
   1. 문자열이 ""(빈문자열)일 경우 
      - 빈 문자열일 경우 정수 0으로 처리하여 리스트에 담는다.
   2. 쉼표(,) 또는 콜론(:)을 구분자로 가지는 문자열일 경우
      - 구분 되어있는 숫자들을 정수로 변환시켜 리스트에 담는다.
   3. 커스텀 구분자를 지정하여 사용하는 경우
      - 커스텀 구분자도 구분자로 지정하여 기존 구분자처럼 사용한다.
   4. 예외 처리 
      - 요구된 입력(구분자와 양수로 구성된 문자열)가 아닌 다른 문자열이 입력으로 들어올 경우 IllegalArgumentException을 발생시킨 후 애플리케이션은 종료시킨다.
3. **덧셈 연산**
   - 숫자 리스트에 있는 숫자들을 덧셈하는 기능이다. 
4. **결과 출력**
   - 덧셈된 값을 '결과 :' 문구와 함계 출력하는 기능이다. 