## `framework`와 `Library`의 차이 

* 제어의 주도권을 누가 가지고 있느냐? 
* 라이브러리, API는 개발자가 가지고 있다. 
* Framework는 f/w가 가지고 있다. 
* Framework가 객체를 생성하면서 객체를 자동으로 필요한 곳에 주입시켜준다. 
* 기반이되는 기능들을 심어준다고 보면된다. 
* Dependency Injection ? 의존관계가 있는 객체를 생성해서 주입을 시켜주는 것
* 주도권을 가져가서 framework가 infrastructure service를 만든다. 
* 

프레임워크?

프레임웤 라이브러리적인 요소를 가지고 있음

개발자가 작성한 클래스를 역호출 하는 구조를 가지고 있다. 

역호출 하는 이유는 뭘까? 

: infrastructual support, plumbing, 기반구조

: byte code injection

기반이 되는 서비스를 제공하기 위해서 개발자가 만든 클래스를 역호출한다. 

바이트코드 인젝션을 통해서 심어준다

IoC (inversion of control

제어의 역전을 구현하는 방법이 2가지 가있다.

1. DI (dependency Injection)의존성 주입

2. DL (dependency Lookup)의존성 찾기 - naming service

3. DI

   setter injection 

   setter method...