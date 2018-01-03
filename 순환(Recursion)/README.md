#### 순환(Recursion)

### What is Recursion?

자기 자신을 호출하는 함수.  
자기 자신을 다시 호출하는 method.  

재귀함수라고 부르기도 한다.  

### Recursion 이 무한루프에 빠지지 않으려면  
1. 코드 상에서 적어도 하나의 recursion에 빠지지 않는 경우가 존재해야 한다.  
2. recursion을 반복하다보면 결국 base case로 수렴해야 한다.  

- 팩토리얼 계산 예제
- x의 n승 계산 예제
- 피보나치 수열 예제
- 최대공약수 계산 예제

### Recursive Thinking
Recursion은 수학함수 계산에만 유용한가?  

반복문으로 해결하는 것들을 recursion 으로 풀 수 있다.  

- 문자열 길이 계산 예제
- 입력한 문자열 화면 출력 예제
- 입력한 문자열 뒤집어 출력 예제
- 2진수 변환 출력 예제
- 배열의 합 구하기 예제


### Recursion VS Iteration

- 모든 순환함수는 반복문(iteration)으로 변경 가능
- 그 역도 성립함. 즉 모든 반복문은 recursion으로 표현 가능함
- 순환함수는 복잡한 알고리즘을 단순하고 알기 쉽게 표현하는 것을 가능하게 함
- 하지만 함수 호출에 따른 오버헤드가 있음 (매개변수 전달, 액티베이션 프레임 생성 등)

### Designing Recursion (순환 알고리즘의 설계)

- 적어도 하나의 base case, 즉 순환되지 않고 종료되는 case가 있어야 한다.
- 모든 case는 결국 base case로 수렴해야 한다.

*암시적(implicit) 매개변수를 명시적(explicit) 매개변수로 바꾸어라.*  

- 순차 탐색 예제


금- 순환 끝내기
