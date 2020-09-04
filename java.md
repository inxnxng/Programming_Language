# STUDY "JAVA"
20200904 - 
[점프 투 자바](https://wikidocs.net/book/31)

## JAVA?

자바로 작성한 파일을 실행하려면
1. `.java` 파일을 `.class` 파일로 바꾸어 주는 컴파일 단계(javac.eve)를 거쳐서
2. `.class` 파일을 실행시킨다 by Java VM(java.exe) 

> 파일명과 클래스명이 동일한 경우 클래스명 앞에 public 키워드를 붙여준다

* public : 메소드의 접근 제어자. <-> private
* static : 메소드에 static이 지정되어 있는 경우 이 메소드는 인스턴스 생성없이 실행 할 수 있음을 의미
* void
* String : 문자열
* args[] : 여러개 값으로 이루어진 배열

## start JAVA

### 변수

* 변수명은 숫자로 시작할 수 없음
* _(underscore)와 $ 문자 외에 특수문자 사용할 수 없음
* 자바 키워드 변수명은 사용 불가능(like int, class, return)

```java
int apple = 2;
String bee = "hello World!";
```

### main method

```java
public class Test {
    public static void main(String[] args){
        System.out.println("Hello World");
    }
}
```
`c:\> java Test a b c` 실행 시 a, b, c가 순서대로 저장된다.

## 자료형

### 숫자

#### 정수 
| 자료형 |                  표현범위                  |
| :----: | :----------------------------------------: |
|  int   |          -2147483648 ~ 2147483647          |
|  long  | -9223372036854775808 ~ 9223372036854775807 |

`long longInt = 9872232434224L;` 이렇게 접미사 `L`을 꼭 붙여야 함

#### boolean

여기서는 bool이 아니라 boolean을 쓴다.