







## @RunWith

application context(=spring bean container 생성)를 만들고 관리하는 작업

RunWith 어노테이션은 각각의 테이스 별로 객체가 생성되더라도 싱글톤의 applicationContext를 보장한다. 

## @Component

빈 스캐닝을 통한 자동인식 Bean 등록 기능을 한다. 

xml에서 <bean>으로 등록하는 대신 클래스 위에 이걸 씀으로써 Bean scanning을 가능하게한다.

규칙 Component("stringPrinter") 앞글자는 소문자, 그리고 Bean scanning할때에 찾는 id값과 동일하게 

그러나 이 어노테이션만 적는다고 스캐닝을 할 수 있는게 아니다. 

그래서 해당 어노테이션을 붙인 패키지명을 xml에 알려줘야한다.

:star: 이부분을 잊으면 찾지못한다. :arrow_down_small:

```xml
<context:component-scan base-package="myspring.di.annot"/>
```



## Bean 등록 Annotation

| @Component  | 컴포넌트를 나타내는 일반적인 스테레오 타입으로 <bean> 태그와 동일한 역할을 한다. |
| ----------- | ------------------------------------------------------------ |
| @Repository | DAO , persistence 레이어, 즉 영속성을 가지는 속성 (파일이나, DB)를 가진 클래스 |
| @Controller | 웹 어플리케이션에서 웹 요청과 응답을 처리하는 클래스         |
| @Service    | 서비스 레이어, 비즈니스 로직을 가진 클래스                   |

>  @Component 외에 것들은 더 특정한 유즈케이스에 대한 @Component의 구체화 된 형태이다. 





---



# 전략3 : XML을 전혀 쓰지않는다.

	#### * config 클래스로 설정을 한다.



