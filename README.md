# java-basic

## Effective Java 3/E 정리
- [Issues](https://github.com/ksw6169/java-basic/issues)
- [WIKI](https://github.com/ksw6169/java-basic/wiki)
  - [아이템 1. 생성자 대신 정적 팩토리 메소드를 고려하라.](https://github.com/ksw6169/java-basic/wiki/%EC%95%84%EC%9D%B4%ED%85%9C-1.-%EC%83%9D%EC%84%B1%EC%9E%90-%EB%8C%80%EC%8B%A0-%EC%A0%95%EC%A0%81-%ED%8C%A9%ED%86%A0%EB%A6%AC-%EB%A9%94%EC%86%8C%EB%93%9C%EB%A5%BC-%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC.)
  - [아이템 2. 생성자에 매개변수가 많다면 빌더를 고려하라.](https://github.com/ksw6169/java-basic/wiki/%EC%95%84%EC%9D%B4%ED%85%9C-2.-%EC%83%9D%EC%84%B1%EC%9E%90%EC%97%90-%EB%A7%A4%EA%B0%9C%EB%B3%80%EC%88%98%EA%B0%80-%EB%A7%8E%EB%8B%A4%EB%A9%B4-%EB%B9%8C%EB%8D%94%EB%A5%BC-%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC.)
  - [아이템 3. private 생성자나 열거 타입으로 싱글턴임을 보증하라.](https://github.com/ksw6169/java-basic/wiki/%EC%95%84%EC%9D%B4%ED%85%9C-3.-private-%EC%83%9D%EC%84%B1%EC%9E%90%EB%82%98-%EC%97%B4%EA%B1%B0-%ED%83%80%EC%9E%85%EC%9C%BC%EB%A1%9C-%EC%8B%B1%EA%B8%80%ED%84%B4%EC%9E%84%EC%9D%84-%EB%B3%B4%EC%A6%9D%ED%95%98%EB%9D%BC.)
  - [아이템 4. 인스턴스화를 막으려거든 private 생성자를 사용하라.](https://github.com/ksw6169/java-basic/wiki/%EC%95%84%EC%9D%B4%ED%85%9C-4.-%EC%9D%B8%EC%8A%A4%ED%84%B4%EC%8A%A4%ED%99%94%EB%A5%BC-%EB%A7%89%EC%9C%BC%EB%A0%A4%EA%B1%B0%EB%93%A0-private-%EC%83%9D%EC%84%B1%EC%9E%90%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.)
  - [아이템 5. 자원을 직접 명시하지 말고 의존 객체 주입을 사용하라.](https://github.com/ksw6169/java-basic/wiki/%EC%95%84%EC%9D%B4%ED%85%9C-5.-%EC%9E%90%EC%9B%90%EC%9D%84-%EC%A7%81%EC%A0%91-%EB%AA%85%EC%8B%9C%ED%95%98%EC%A7%80-%EB%A7%90%EA%B3%A0-%EC%9D%98%EC%A1%B4-%EA%B0%9D%EC%B2%B4-%EC%A3%BC%EC%9E%85%EC%9D%84-%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.)
  - [아이템 6. 불필요한 객체 생성을 피하라.](https://github.com/ksw6169/java-basic/wiki/%EC%95%84%EC%9D%B4%ED%85%9C-6.-%EB%B6%88%ED%95%84%EC%9A%94%ED%95%9C-%EA%B0%9D%EC%B2%B4-%EC%83%9D%EC%84%B1%EC%9D%84-%ED%94%BC%ED%95%98%EB%9D%BC.)
  - [아이템 7. 다 쓴 객체 참조를 해제하라.](https://github.com/ksw6169/java-basic/wiki/%EC%95%84%EC%9D%B4%ED%85%9C-7.-%EB%8B%A4-%EC%93%B4-%EA%B0%9D%EC%B2%B4-%EC%B0%B8%EC%A1%B0%EB%A5%BC-%ED%95%B4%EC%A0%9C%ED%95%98%EB%9D%BC.)
  - [아이템 8. finalizer와 cleaner 사용을 피하라.](https://github.com/ksw6169/java-basic/wiki/%EC%95%84%EC%9D%B4%ED%85%9C-8.-finalizer%EC%99%80-cleaner-%EC%82%AC%EC%9A%A9%EC%9D%84-%ED%94%BC%ED%95%98%EB%9D%BC.)
  - [아이템 9. try-finally 보다는 try-with-resources를 사용하라.](https://github.com/ksw6169/java-basic/wiki/%EC%95%84%EC%9D%B4%ED%85%9C-9.-try-finally-%EB%B3%B4%EB%8B%A4%EB%8A%94-try-with-resources%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.)
  - [아이템 10. equals는 일반 규약을 지켜 재정의하라.](https://github.com/ksw6169/java-basic/wiki/%EC%95%84%EC%9D%B4%ED%85%9C-10.-equals%EB%8A%94-%EC%9D%BC%EB%B0%98-%EA%B7%9C%EC%95%BD%EC%9D%84-%EC%A7%80%EC%BC%9C-%EC%9E%AC%EC%A0%95%EC%9D%98%ED%95%98%EB%9D%BC.)
  - [아이템 11. equals를 재정의하려거든 hashCode도 재정의하라.](https://github.com/ksw6169/java-basic/wiki/%EC%95%84%EC%9D%B4%ED%85%9C-11.-equals%EB%A5%BC-%EC%9E%AC%EC%A0%95%EC%9D%98%ED%95%98%EB%A0%A4%EA%B1%B0%EB%93%A0-hashCode%EB%8F%84-%EC%9E%AC%EC%A0%95%EC%9D%98%ED%95%98%EB%9D%BC.)
  - [아이템 12. toString을 항상 재정의하라.](https://github.com/ksw6169/java-basic/wiki/%EC%95%84%EC%9D%B4%ED%85%9C-12.-toString%EC%9D%84-%ED%95%AD%EC%83%81-%EC%9E%AC%EC%A0%95%EC%9D%98%ED%95%98%EB%9D%BC.)
  - [아이템 13. clone 재정의는 주의해서 진행하라.](https://github.com/ksw6169/java-basic/wiki/%EC%95%84%EC%9D%B4%ED%85%9C-13.-clone-%EC%9E%AC%EC%A0%95%EC%9D%98%EB%8A%94-%EC%A3%BC%EC%9D%98%ED%95%B4%EC%84%9C-%EC%A7%84%ED%96%89%ED%95%98%EB%9D%BC.)
  - [아이템 14. Comparable을 구현할지 고려하라.](https://github.com/ksw6169/java-basic/wiki/%EC%95%84%EC%9D%B4%ED%85%9C-14.-Comparable%EC%9D%84-%EA%B5%AC%ED%98%84%ED%95%A0%EC%A7%80-%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC.)
  - [아이템 15. 클래스와 멤버의 접근 권한을 최소화하라.](https://github.com/ksw6169/java-basic/wiki/%EC%95%84%EC%9D%B4%ED%85%9C-15.-%ED%81%B4%EB%9E%98%EC%8A%A4%EC%99%80-%EB%A9%A4%EB%B2%84%EC%9D%98-%EC%A0%91%EA%B7%BC-%EA%B6%8C%ED%95%9C%EC%9D%84-%EC%B5%9C%EC%86%8C%ED%99%94%ED%95%98%EB%9D%BC.)
  - [아이템 16. public 클래스에서는 public 필드가 아닌 접근자 메소드를 사용하라.](https://github.com/ksw6169/java-basic/wiki/%EC%95%84%EC%9D%B4%ED%85%9C-16.-public-%ED%81%B4%EB%9E%98%EC%8A%A4%EC%97%90%EC%84%9C%EB%8A%94-public-%ED%95%84%EB%93%9C%EA%B0%80-%EC%95%84%EB%8B%8C-%EC%A0%91%EA%B7%BC%EC%9E%90-%EB%A9%94%EC%86%8C%EB%93%9C%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.)
  - [아이템 17. 변경 가능성을 최소화하라.](https://github.com/ksw6169/java-basic/wiki/%EC%95%84%EC%9D%B4%ED%85%9C-17.-%EB%B3%80%EA%B2%BD-%EA%B0%80%EB%8A%A5%EC%84%B1%EC%9D%84-%EC%B5%9C%EC%86%8C%ED%99%94%ED%95%98%EB%9D%BC.)
  - [아이템 18. 상속보다는 컴포지션을 사용하라.](https://github.com/ksw6169/java-basic/wiki/%EC%95%84%EC%9D%B4%ED%85%9C-18.-%EC%83%81%EC%86%8D%EB%B3%B4%EB%8B%A4%EB%8A%94-%EC%BB%B4%ED%8F%AC%EC%A7%80%EC%85%98%EC%9D%84-%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.)
  - 아이템 19. 상속을 고려해 설계하고 문서화하라. 그러지 않았다면 상속을 금지하라.
  - 아이템 20. 추상 클래스보다는 인터페이스를 우선하라.
  - 아이템 21. 인터페이스는 구현하는 쪽을 생각해 설계하라.
  - 아이템 22. 인터페이스는 타입을 정의하는 용도로만 사용하라.
  - 아이템 23. 태그 달린 클래스보다는 클래스 계층구조를 활용하라.
  - 아이템 24. 멤버 클래스는 되도록 static으로 만들라.
  - 아이템 25. 톱레벨 클래스는 한 파일에 하나만 담으라.
