## Java 선택과 반복
### 1) 제어문
- 프로그램에서 문장은 기본적으로 순차적으로 실행되는데, 복잡한 문장을 해결하기 위해서는 제어문이 필요함
- 조건문 = 조건에 따라서 여러 개의 실행 경로 가운데 하나를 선택할 때 사용하는 것
- 반복문 = 조건이 유지되는 한 혹은 정해진 횟수 만큼 처리를 되풀이하는 문장

### 2) if- else문
```java
if(number > 0){ 
  System.out.println("양수입니다");
}
else{
  System.out.println("음수입니다");
}
```
- if문에서는 조건을 수식으로 표현함.
- 조건식이 참이면 문장을 실행하고 거짓이면 else의 문장을 실행함.
- if-else문에서 else부분이 생략될 수 있음

### 2) switch문
```java
public class Main {
	public static void main(String[] args) {
		switch(변수)
		{
		case c1:
			처리문장1;
			break;
		case c2:
			처리문장2;
			break;
		default:
			처리문장;
			break;
		}
	}
}
```
- 가능한 실행 경로가 많은 경우에는 switch문을 사용
- switch문에서는 변수의 값을 계산하여 case의 뒤에 계산함
- 변수에 맞는 곳으로 이동함, c1.c2. 등으로 이동하는 것
- c1,c2로 이동한 후에 처리 문장을 실행하고 break;를 하면 마무리됨.

### 3) while문
```java
public class Main {
	public static void main(String[] args) {
		while(조건식){
			문장1;
			문장2;
		}
	}
}
``` 
- 어떤 조건을 정해놓고 반복을 하는 구조. 미리 반복 횟수를 알 수 없는 경우에 사용하는 구조
- 조건을 만족하는 동안에 문장1, 문장2를 실행하도록 함.

### 4) do-while문
```java
public class Main {
	public static void main(String[] args) {
		do
		{
			문장1;
			문장2;
		}whil(조건);
	}
}
```
- do-while문은 while문과 비슷하나 반복 조건을 루프의 처음이 아니라 루프의 끝에서 검사한다는 점이 다르다
- do-while문에서는 먼저 문장을 실행한 후에 조건이 맞는지 아닌지 확인한다.

### 5) for문
```java
public class Main {
	public static void main(String[] args) {
		for(초기식;조건식;증감식)  
		{
			반복문장;
		}
	}
}
```
- 초기식 = 반복 루프를 시작하기 전에 한번만 실행된다. 변수 값을 초기화하는 용도
- 조건식 = 반복의 조건을 검사하는 수식, 조건식이 거짓이 되면 반복을 중단하도록 함.
- 증감식 = 한번의 루프 실행이 끝나면 증감식이 실행된다. 

### 6) 중첩 반복문
```java
public class Main {
	public static void main(String[] args) {
		for(int i=0;i<4;i++){
			for(k=0;k<5;k++) {
				반복문장;
			}
		}
	}
}
```
- 중첩반복문 = 반복문 안에 다른 반복문이 실행되는 형태
- 밖에 있는 반복문을 외부 반복문이고, 안에 있는 반복문은 내부 반복문이라고 함.

### 7) break와 continue
- break는 조건을 만족하는 경우에 그 조건을 빠져나와서 아예 종료하는 것.
- continue는 조건을 만족하는 부분만 마무리하고 다시 진행하도록 하는 것.




