## MyBatis

#### * myBatis 에서의 namespace란? 

​	SqlSessionFactory 에서 

userMapper, studentMapper ....등 *Mapper.xml 로 끝나는 애들을 모두 끌어모은다.

다른사람이 내가 만든 select id 와 동일하게 적었는지 계속 체크해야할 수도 있다.

왜냐하면 메모리상에 한꺼번에 쭉 끌어당겨서 모으기때문이다.

그렇기 때문에 각각의 mapper마다 namespace를 다르게 주면 id가 겹쳐도 충돌이 나지않느는다. 



1:1 관계에서는 association을 쓴다. 즉 

객체끼리 넣을 때에는 association을 쓴다. 

결과 값을 매핑을 다 해줘야한다. 



모든것은 sqlsession을 만들어주기 위한 과정이다.

sqlMapconfig usermppaer sqlsessionfactory...등등

:thumbsup:

:book



