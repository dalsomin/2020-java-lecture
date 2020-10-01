access layer

persistence

rest 는 serializable 이 필요없다 .

restController 는 json으로 받는다. 

데이터소스를 쓰려면 

해당되는 커넥션 정보가 들어가 져야한다. 



persistence 아닌건 enitty

## syncronus로 서비스한다는게 무슨말이지? 



도메인객체를 @id, @entity

dto객체로 싱크로너스로 할려면 serailizable로 해야하는데

only json이면 

혼동될까봐 id entity 를 빼준것

book을 다시 할당해준것은 해당되는 find에서 가져온 데이터를 수정했으면 

update(Book book ) 

## @repository 와 @service의 차이점 알아내기 

빌트 툴 
ant라는 xml형식으로 작성햇었는데 
xml로 작성하다보니 너무 어렵고관리가 어려워서
repository에주고 
lib에는 카피하지않게 
maven은 여전히 xml 기반이다. 
그래서 syntax, 계층 주기도 어렵고 
좀더 쓰기 쉽게 json형태로 들여쓰기로 쉽게 쓸수있게 
xml기반을 더 쉽게 빌드 하기 쉽게 만들어놓은게 gradle이다. 
차이점은 pom.xml 이 불편해서 
yaml file처럼 해놓은게 gradle이다. 