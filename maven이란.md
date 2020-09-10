## maven이란? 

maven이 없을때에는 몽고db driver사이트에가서 jar를 다운로드 받아서

jar classpath를 직접 잡아줬어야했다. 불편 :anger:

npm = node package manager 같은 개념이다

자바진영에서의 npm 이 maven 이다. 

프로젝트관리도 해주지만 라이브러리 관리도 해주는 게 maven ! 



maven repository 로 가보자

https://mvnrepository.com/



가서 mongo java driver을 찾는다. 

https://mvnrepository.com/artifact/org.mongodb/mongo-java-driver



최신버전을 클릭하면 이런 코드가 나온다.

:arrow_down_small: 이코드를 복사를 한다. 

```xml
<!-- https://mvnrepository.com/artifact/org.mongodb/mongo-java-driver -->
<dependency>
    <groupId>org.mongodb</groupId>
    <artifactId>mongo-java-driver</artifactId>
    <version>3.12.7</version>
</dependency>
```



다시 npm과 비교를 해보자면 npm에서 어떤 드라이버를 install 하고 싶으면 

`npm install jquery` 라고 명령어를 치고, 그 의존성관계가 

`package.json`에 등록되지만

자바진영에서의 npm인 `maven` 에서는 `dependency`를 준다.	

어디에? `pom.xml`안에 `dependency`를 해주는 것! 



그럼 maven을 적용하는 방식에는 :v:2가지가 있다.

> 1. java project 를 maven project로 `convert`시키는 방식.
> 2. 아예 처음부터 maven project로 시작하기 



프로젝트에서 오른쪽마우스 클릭 -> configure -> convert to maven project







