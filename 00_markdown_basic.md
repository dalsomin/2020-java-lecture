# 마크다운(Markdown)

> 일반텍스트 형식 구문을 사용하는 마크업 언어의 일종으로 사용법이 쉽고 간결하여 빠르게 문서정리를 할 수 있습니다. 단, 모든 HTML 마크업을 대체하지는 않습니다.



## 1.문법

### 1.1Header

> 헤더는 제목을 표현할때 사용합니다. 단순히 글자의 크기를 표현하는 것이 아닌 의미론적인 중요도를 나타냅니다.

* `<h1>`부터 `<h6>` 까지 표현가능합니다.
* `#` 의 개수로 표현하거나 `<h1></h1>` 의 형태로 표현가능함.



#	h1

## h2

### h3

#### h4

##### h5

###### h6

### 1.2 List

> 목록을 나열할때 사용한다. 순서가 필요한 항목과 그렇지 않은 항목으로 구분할 수 있다. 순서가 있는 항목아래 순서가 없는 항목을 지정할 수 있으며 그반대또한 가능하다.

* 순서가 없는 목록
  * `1.`을 누르고 스페이스바를 누르면 생성할 수 있다.
  * `tab` 키를 눌러서 하위항목을 생성할 수 있고 `shift + tab` 키를 눌러서 상위항목으로 이동할 수 있다.
* 순서가 있는 목록
  * `-`(하이픈) 을 쓰고 스페이스 바를 누르면 생성할 수 있다.
  * `tab` 키를 눌러서 하위항목을 생성할 수 있고 `shift + tab` 키를 눌러서 상위항목으로 이동할 수 있다.

1. 순서가 있는 항목
2. 순서가 있는 항목
   1. 순서있는 하위항목
   2. 순서있는 하위항목

- 순서 없는 항목
- 순서 없는 항목
  - 순서없는 하위항목
  - 순서없는 하위항목



### 1.3 Code Block

> 코드블럭은 작성한 코드를 정리하거나 강조하고 싶은 부분을 나타낼때 사용한다. 인라인과 블럭단위로 구분할 수 있다.

- inline
  - inline으로 처리하고 싶다면 백틱으로 감싼다.
- Block
  - block으로 처리하고싶다면  백틱을 3번 누르고`enter`누른다.

`add`한 요소를 remote 저장소에 올리려면 `$ git push origin master`을 터미널에 입력합니다.

```bash
$ git add
$ git commit -m "first commit"
$ git push origin master
```



### 1.4 Image

> 로컬에 있는 이미지를 삽입하거나 이미지 링크를 화용하여 이미지를 나타낼때 사용한다.

- `![]()`를 작성하고 `()`안에 이미지 주소를 입력한다. `[]`안에는 이미지 파일의 이름을 작성한다.
- 로컬에 이미지 파일을 저장한 경우 절대 경로가 아닌 상대 경로를 사용하여 이미지를 저장한다.



![](https://miro.medium.com/max/875/1*BCZkmZR1_YzDZy22Vn4uUw.png){: width="100" height="100"}



---

###	1.5 Link

> 특정 주소로 링크를 걸때 사용합니다.

* `[]()`를 작성하고 `()` 안에 링크주소를 작성하고 `[]`주소안에 어떤 링크주소인지 작성합니다.
* [깃이미지 링크](https%3A%2F%2Fmiro.medium.com%2Fmax%2F1200%2F1*BCZkmZR1_YzDZy22Vn4uUw.png&imgrefurl=https%3A%2F%2Fmedium.com%2F%40pks2974%2F%25EC%259E%2590%25EC%25A3%25BC-%25EC%2582%25AC%25EC%259A%25A9%25ED%2595%2598%25EB%258A%2594-%25EA%25B8%25B0%25EC%25B4%2588-git-%25EB%25AA%2585%25EB%25A0%25B9%25EC%2596%25B4-%25EC%25A0%2595%25EB%25A6%25AC%25ED%2595%2598%25EA%25B8%25B0-533b3689db81&tbnid=03d8Sbid2U3P7M&vet=12ahUKEwje3Mywr7XrAhUAy4sBHWKfDh0QMygAegUIARCnAQ..i&docid=OaGu61UKeMG7gM&w=910&h=380&q=git%20%EC%9D%B4%EB%AF%B8%EC%A7%80&ved=2ahUKEwje3Mywr7XrAhUAy4sBHWKfDh0QMygAegUIARCnAQ)
* [구글](www.google.com)

---

### 1.6 Table

> 표를 작성하여 요소를 구분할 수 있습니다.

* `|`(파이프) 사이에 컬럽을 작성하고 `enter`를 입력합니다.
* 마지막 칼럼을 작성하고 뒤에 `|`를 붙여줍니다.

| git  | git blog | git page |
| ---- | -------- | -------- |
| 1    | 2        | 3        |
| 0    | 0        | 0        |
| 1    | 2        | 3        |

---

### 1.7 기타

#### 인용문

* `>`를 입력하고 `enter`키를 누른다.

  > ​	git은 컴퓨터 파일의 변경사항을  추적하고 여러명의 사용자들간에 해당파일들의 작업을 조율하기 위한 분산버전 관리 시스템이다.
  >
  > > 중첩 사용가능
  > >
  > > > 으와

  ---

---

#### 강조

* *이탤릭체*
* **보드체**
* ~~취소선~~

---



# Local Computer

1. git은 폴더단위로 관리한다. 

2.  git은 프로젝트를 관리하면서 배우는 소프트 웨어이다. 지울때 고민없이 지워도 된다. 

   ```bash
   $ git init (폴더단위로 git을 시작하겠다.라는 명령어)
   Initialized empty Git repository in C:/users/Til/.git/
   
   $ ls -a (숨김파일 조회)
   ./ ../ .git/
   $ cd .git/ (여기는 설정파일이 있는 곳인데 들어갈꺼야? 건드리지마! 라는 경고가 뜬다.)
   config  description  HEAD  hooks/  info/  objects/  refs/
   $ cd ..
   $ ls -a
   $ rm -r .git/
   
   ```

   

3.   :star:**git에서 조심해야할 부분**  :star:

   태양은 하나다. 즉 상위폴더에 .git 폴더가 있다면 하위폴더에 .git 을 또다시 만들면 안된다. 

   즉 하위폴더에 있는 .git 을 지우는게 가장 빠르다. 상위폴더 하나로 관리하는 것이 베스트. 

4.  ```bash
   $ cp ()
   $ mv (파일을 이동할때, 그리고 파일명을 바꿀때도 쓰기때문에 주의해야한다. 복사하고자하는 폴더로 이동을 한 후에 써야한다.)
   $ mv (복사하고자하는 파일이 있는 폴더) .(현재폴더)
   ```

5. ```bash
   $ git status (git을 쓰면서 가장많이 쓸 명령어.)
   ```

6.  ```bash
   # git commit (snap shot을 찍다. . . .)
   그런데 또 git에서는 바로 사진 찍는게 아니고...
   이건 안찍고싶거든...하는 파일이 있으면 제외할 수 있다구...
   그래서 무대위에 올려논것만 commit 하게 끔 할수있따!!
   ```

7. ```bash
   $ git add . (스테이징에 올리는 명령어- Staging area)
   ```

8. ```bash
   $ git commit 만 쓰면 누구냐고 물어본다. 
   who you are !!
   ```

9. ```bash
   $ git config --global user.email "xxxx@gmail.com"
   $ git config --global user.name "somin"
   ```

10. ```bash
    $ git log
    $ git log --oneline -1
    $ git log --oneline -10
    ```



---

## Remote Repository 와 연결

1. ```bash
   $ git remote 를 해보면 아무것도 안나온다. 즉 원격 레포지터리에 연결이 되지 않았다는 의미이다.
   ```

2.  ```bash
   $ git remote add origin https://github.com/dalsomin/TIL.git
   ```




##	Version Control Command

```bash 
$ git log --oneline
$ git checkout XXXXX[해시코드] (그 커밋시점버전으로 돌아가기)
$ git checkout master (다시돌아오기)
```



