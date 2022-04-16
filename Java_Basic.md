## Java 기초 개념알기
### 1) 클래스
```java
public class Hello {

	}
}
```
- 클래스는 자바와 같은 객체 지향 언어의 기본적인 빌딩 블록
- 자바에는 적어도 하나의 클래스는 필요함
- public = 이 클래스의 사용 범위를 알려줌. 누구나 사용 가능
- class = 클래스 임을 선언해주는 부분
- Hello = 클래스의 이름을 선언해주는 부분
- 자바에서 소스파일의 이름은 항상 public이 붙은 클래스의 이름과 동일하여햐 함

### 2) 메소드
```java
public class Hello {
	public static void main(String[] args) {
		
	}
}
```
- 메소드는 특정한 작업을 수행하는 코드의 묶음
- 클래스 내부에 정의되는 부분으로 기능을 담당함
- static = 정적인 메소드
- void = 반환값이 없는, 결과값을 반환하지 않음
- String[] args = 외부에서 주어지는 데이터를 받는 매개 수

### 3) 문장
```java
public class Hello {
	public static void main(String[] args) {
		System.out.println("Hello World");
	}
}
``` 
- System.out.println("Hello World"); = 작업의 내용을 기술한 부분
- System.out.println() = 화면에 출력할 때 사용하는 메소드
- ;는 문장을 마친다는 의미로 항상 세미콜론을 붙여주어야 함

### 4) 변수
```java
int value;        // int는 자료형
int value = 9;    // 9라는 값을 넣어주어 초기화함
```
- 변수는 데이터를 담아두는 상자
- 사용하기 전에 미리 컴파일러에게 어떤 변수를 사용하겠다고 선언해야 함
- 선언을 통해 변수의 자료형에 맞는 공간을 할당함

### 5) 자료형
- 자료형은 변수엥 저장되는 데이터의 타입을 의미함
))

### 6) res > minmap
- minmap은 ic_launcher등, 기본적으로 제공하는 아이콘들을 모아놓은 곳
