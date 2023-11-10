Interface
============

JFC를 사용하다 보면 ArrayList와 LinkedList 클래스를 혼동한다.</br>
왜 자바는 두 가지 구현을 제공할까?</br></br>

자바 인터페이스
-----------
자바 Interface는 메서드 집합을 의미한다.</br>
Java.lang 패키지에 정의된 Comparable interface의 소스 코드는 다음과 같다.

``` java
public interface Comparable<T>{
    public int compareTo(T o);
}
```
Comparable은 자기 자신과 매개 변수를 비교한다.
