## JDBC

java는 어떤 특정 벤더에 종속되지 않게끔해야하기 때문에 

오라클을 쓰던 mysql을 쓰던 즉 DB 벤더를 뭘 쓰던 코드가 유지되어야한다. 



oracle.jdbc.driver.OracleDriver

new OracleDriver();

왜 이렇게 안하고 

이렇게 했을까? 

이렇게 하면 

우리가 오라클드라이버를 직접  임포트 해줘야한다. 

만약에 디비를 바꾸면 또 new 해줘야하기때문에 

나중에 classForname 만 바꿔주면 되게끔

특정 디비에 

lang Class.forName("")으로 하면 나중에 드라이버 클래스 이름만 알려주면

해당 클래스만 찾아서 객체 생성해주는 게 class.forName 이라고 한다. 







ojdbc6.jar 를 복사하고 build path-library에 추가를 해준다. 

그러면 reference Library 에 추가가 된다. 

그후 jdbc 폴더를 생성한다. 



