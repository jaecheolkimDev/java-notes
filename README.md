JAVA 공부 노트
=============

더블콜론(::)
-------------
> 메서드 참조 종류
>  > 어떠한 메서드를 참조하여 실행하느냐에 메소드 참조도 종류가 나뉘게 된다.
|종류|람다 표현식|메서드 참조|
|------|---|---|
|정적 메서드 참조|(x) -> ClassName.method(x)|ClassName::method|
|인스턴스 메서드 참조|(x) -> obj.method(x)|obj::method|
|매개변수의 메서드 참조|(obj, x) -> obj.method(x)|ClassName::method|
|생성자 참조|(x, y) -> new ClassName(x, y)|ClassName::new|
