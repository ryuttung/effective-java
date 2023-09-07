# Effective Java Study
<img width="765" alt="image" src="https://github.com/joshua-study/effective-java/assets/64997253/768b518f-01c2-4377-bc26-dd02babaff82">

- [스터디 운영](https://effective-java.notion.site/Rule-e5c19c6637194f8e9e042bd5eaea1948?pvs=4)
- [이펙티브 자바 공식 Github](https://github.com/WegraLee/effective-java-3e-source-code)
- [용어 해설집](https://docs.google.com/document/d/1Nw-_FJKre9x7Uy6DZ0NuAFyYUCjBPCpINxqrP0JFuXk/edit)

<br>

## 2장. 객체 생성과 파괴

| 아이템                                                                                             | 발표자료                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|-------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [아이템 1. 생성자 대신 정적 팩터리 메서드를 고려하라](https://github.com/joshua-study/effective-java/issues/1)       | [이재훈](https://github.com/joshua-study/effective-java/blob/main/02%EC%9E%A5/01_%EC%83%9D%EC%84%B1%EC%9E%90%20%EB%8C%80%EC%8B%A0%20%EC%A0%95%EC%A0%81%20%ED%8C%A9%ED%86%A0%EB%A6%AC%20%EB%A9%94%EC%86%8C%EB%93%9C%EB%A5%BC%20%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC_%EC%9D%B4%EC%9E%AC%ED%9B%88.md) / [김선만](https://github.com/joshua-study/effective-java/blob/main/02%EC%9E%A5/01_%EC%83%9D%EC%84%B1%EC%9E%90%20%EB%8C%80%EC%8B%A0%20%EC%A0%95%EC%A0%81%20%ED%8C%A9%ED%86%A0%EB%A6%AC%20%EB%A9%94%EC%86%8C%EB%93%9C%EB%A5%BC%20%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC_%EA%B9%80%EC%84%A0%EB%A7%8C.md) / [지선학](https://github.com/joshua-study/effective-java/blob/main/02%EC%9E%A5/01_%EC%83%9D%EC%84%B1%EC%9E%90%20%EB%8C%80%EC%8B%A0%20%EC%A0%95%EC%A0%81%20%ED%8C%A9%ED%86%A0%EB%A6%AC%20%EB%A9%94%EC%86%8C%EB%93%9C%EB%A5%BC%20%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC_%EC%A7%80%EC%84%A0%ED%95%99.md) / [장병준](https://github.com/joshua-study/effective-java/blob/main/02%EC%9E%A5/01_%EC%83%9D%EC%84%B1%EC%9E%90%20%EB%8C%80%EC%8B%A0%20%EC%A0%95%EC%A0%81%20%ED%8C%A9%ED%86%A0%EB%A6%AC%20%EB%A9%94%EC%86%8C%EB%93%9C%EB%A5%BC%20%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC_%EC%9E%A5%EB%B3%91%EC%A4%80.md) / [류승연](https://github.com/joshua-study/effective-java/blob/main/02%EC%9E%A5/01_%20%EC%83%9D%EC%84%B1%EC%9E%90%20%EB%8C%80%EC%8B%A0%20%EC%A0%95%EC%A0%81%20%ED%8C%A9%ED%86%A0%EB%A6%AC%20%EB%A9%94%EC%86%8C%EB%93%9C%EB%A5%BC%20%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC_%EB%A5%98%EC%8A%B9%EC%97%B0.md)                               |
| [아이템 2. 생성자에 매개변수가 많다면 빌더를 고려하라](https://github.com/joshua-study/effective-java/issues/2)       | [이재훈](https://github.com/joshua-study/effective-java/blob/main/02%EC%9E%A5/02_%EC%83%9D%EC%84%B1%EC%9E%90%EC%97%90%20%EB%A7%A4%EA%B0%9C%EB%B3%80%EC%88%98%EA%B0%80%20%EB%A7%8E%EB%8B%A4%EB%A9%B4%20%EB%B9%8C%EB%8D%94%EB%A5%BC%20%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC_%EC%9D%B4%EC%9E%AC%ED%9B%88.md) / [김선만](https://github.com/joshua-study/effective-java/blob/main/02%EC%9E%A5/02_%EC%83%9D%EC%84%B1%EC%9E%90%EC%97%90%20%EB%A7%A4%EA%B0%9C%EB%B3%80%EC%88%98%EA%B0%80%20%EB%A7%8E%EB%8B%A4%EB%A9%B4%20%EB%B9%8C%EB%8D%94%EB%A5%BC%20%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC_%EC%9D%B4%EC%9E%AC%ED%9B%88.md) / [지선학](https://github.com/joshua-study/effective-java/blob/main/02%EC%9E%A5/02_%EC%83%9D%EC%84%B1%EC%9E%90%EC%97%90%20%EB%A7%A4%EA%B0%9C%EB%B3%80%EC%88%98%EA%B0%80%20%EB%A7%8E%EB%8B%A4%EB%A9%B4%20%EB%B9%8C%EB%8D%94%EB%A5%BC%20%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC_%EC%A7%80%EC%84%A0%ED%95%99.md) / [장병준](https://github.com/joshua-study/effective-java/blob/main/02%EC%9E%A5/02_%EC%83%9D%EC%84%B1%EC%9E%90%EC%97%90%20%EB%A7%A4%EA%B0%9C%EB%B3%80%EC%88%98%EA%B0%80%20%EB%A7%8E%EB%8B%A4%EB%A9%B4%20%EB%B9%8C%EB%8D%94%EB%A5%BC%20%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC_%EC%9E%A5%EB%B3%91%EC%A4%80.md) / [류승연](https://github.com/joshua-study/effective-java/blob/main/02%EC%9E%A5/02_%20%EC%83%9D%EC%84%B1%EC%9E%90%EC%97%90%20%EB%A7%A4%EA%B0%9C%EB%B3%80%EC%88%98%EA%B0%80%20%EB%A7%8E%EB%8B%A4%EB%A9%B4%20%EB%B9%8C%EB%8D%94%EB%A5%BC%20%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC_%EB%A5%98%EC%8A%B9%EC%97%B0.md) |
| [아이템 3. private 생성자나 열거 타입으로 싱글턴임을 보증하라](https://github.com/joshua-study/effective-java/issues/3) | [이재훈](https://github.com/joshua-study/effective-java/blob/main/02%EC%9E%A5/03_%20private%20%EC%83%9D%EC%84%B1%EC%9E%90%EB%82%98%20%EC%97%B4%EA%B1%B0%20%ED%83%80%EC%9E%85%EC%9C%BC%EB%A1%9C%20%EC%8B%B1%EA%B8%80%ED%84%B4%EC%9E%84%EC%9D%84%20%EB%B3%B4%EC%A6%9D%ED%95%98%EB%9D%BC_%EC%9D%B4%EC%9E%AC%ED%9B%88.md) / [지선학](https://github.com/joshua-study/effective-java/blob/main/02%EC%9E%A5/03_private%20%EC%83%9D%EC%84%B1%EC%9E%90%EB%82%98%20%EC%97%B4%EA%B2%A8%20%ED%83%80%EC%9E%85%EC%9C%BC%EB%A1%9C%20%EC%8B%B1%EA%B8%80%ED%84%B4%EC%9E%84%EC%9D%84%20%EB%B3%B4%EC%A6%9D%ED%95%98%EB%9D%BC_%EC%A7%80%EC%84%A0%ED%95%99.md) / [류승연](https://github.com/joshua-study/effective-java/blob/main/02%EC%9E%A5/03_%20private%20%EC%83%9D%EC%84%B1%EC%9E%90%EB%82%98%20%EC%97%B4%EA%B1%B0%20%ED%83%80%EC%9E%85%EC%9C%BC%EB%A1%9C%20%EC%8B%B1%EA%B8%80%ED%84%B4%EC%9E%84%EC%9D%84%20%EB%B3%B4%EC%A6%9D%ED%95%98%EB%9D%BC_%EB%A5%98%EC%8A%B9%EC%97%B0.md) /                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| [아이템 4. 인스턴스화를 막으려거든 private 생성자를 사용하라](https://github.com/joshua-study/effective-java/issues/4) | [이재훈](https://github.com/ljh468/effective-java/blob/main/02%EC%9E%A5/04_%20%EC%9D%B8%EC%8A%A4%ED%84%B4%EC%8A%A4%ED%99%94%EB%A5%BC%20%EB%A7%89%EC%9D%B4%EB%A0%A4%EA%B1%B0%EB%93%A0%20private%20%EC%83%9D%EC%84%B1%EC%9E%90%EB%A5%BC%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC_%EC%9D%B4%EC%9E%AC%ED%9B%88.md) / [김선만](https://github.com/joshua-study/effective-java/blob/main/02%EC%9E%A5/04_%EC%9D%B8%EC%8A%A4%ED%84%B4%EC%8A%A4%ED%99%94%EB%A5%BC%20%EB%A7%89%EC%9C%BC%EB%A0%A4%EA%B1%B0%EB%93%A0%20private%20%EC%83%9D%EC%84%B1%EC%9E%90%EB%A5%BC%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC_%EA%B9%80%EC%84%A0%EB%A7%8C.md) / [지선학](https://github.com/joshua-study/effective-java/blob/main/02%EC%9E%A5/04_%EC%9D%B8%EC%8A%A4%ED%84%B4%EC%8A%A4%ED%99%94%EB%A5%BC%20%EB%A7%89%EC%9C%BC%EB%A0%A4%EA%B1%B0%EB%93%A0%20private%20%EC%83%9D%EC%84%B1%EC%9E%90%EB%A5%BC%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC_%EC%A7%80%EC%84%A0%ED%95%99.md) / [류승연](https://github.com/joshua-study/effective-java/blob/main/02%EC%9E%A5/04_%20%EC%9D%B8%EC%8A%A4%ED%84%B4%EC%8A%A4%ED%99%94%EB%A5%BC%20%EB%A7%89%EC%9D%B4%EB%A0%A4%EA%B1%B0%EB%93%A0%20private%20%EC%83%9D%EC%84%B1%EC%9E%90%EB%A5%BC%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC_%EB%A5%98%EC%8A%B9%EC%97%B0.md)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| [아이템 5. 자원을 직접 명시하지 말고 의존 객체 주입을 사용하라](https://github.com/joshua-study/effective-java/issues/23)| [이재훈]() / [김선만]() / [지선학]() / [장병준]() / [류승연]()                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [아이템 6. 불필요한 객체 생성을 피하라](https://github.com/joshua-study/effective-java/issues/24)              |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [아이템 7. 다 쓴 객체 참조를 해제하라](https://github.com/joshua-study/effective-java/issues/25)              |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [아이템 8. finalizer와 cleaner 사용을 피하라](https://github.com/joshua-study/effective-java/issues/26)   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [아이템 9. try-finally보다는 try-with-resources를 사용하라](https://github.com/joshua-study/effective-java/issues/27) |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [아이템 10. equals는 일반 규약을 지켜 재정의하라](https://github.com/joshua-study/effective-java/issues/27)     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [아이템 11. equals를 재정의하려거든 hashCode도 재정의하라](https://github.com/joshua-study/effective-java/issues/27) |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [아이템 12. toString을 항상 재정의하라](https://github.com/joshua-study/effective-java/issues/27)          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [아이템 13. clone 재정의는 주의해서 진행하라](https://github.com/joshua-study/effective-java/issues/27)        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [아이템 14. Comparable을 구현할지 고려하라]()                                                               |
| [아이템 15. 클래스와 멤버의 접근 권한을 최소화하라]()                                                               |
| [아이템 16. public 클래스에서는 public 필드가 아닌 접근자 메서드를 사용하라]()                                           |
| [아이템 17. 변경 가능성을 최소화하라]()                                                                                            |
| [아이템 18. 상속보다는 컴포지션을 사용하라]()                                                                                            |



## 3장. 모든 객체의 공통 메서드

## 4장. 클래스와 인터페이스

## 5장. 제네릭
