```bash
$ git branch 
# 현재 저장소에 있는 모든 branch를 출력하고 & 현재위치의 브랜치를 표시해준다 
```

```bash
$ git branch [새롭게 생성할 브랜치명]
# 새로운 브랜치를 생성하는 명령어 
```

```bash
$ git checkout [이동할 브랜치명]
# 이동하고 싶은 브랜치로 이동하는 명령어 
```

```bash
$ HEAD 는 포인터이다. 
$ 각각의 커밋이 노드라고 생각하고 HEAD가 포인터로서 작동되는 것이다. 
```

>  `git`이 가벼운 이유는 (LinkedList)노드객체가 본인의 [데이터] +자기 이전노드의 [포인터]

```bash
$ git merge [브랜치명]
# 주의 ! ! ! 
# 병합의 주체가 되는 브랜치로 이동후에 머지를 해야한다. 
```

:kissing_smiling_eyes: 

:heavy_check_mark:

:

## Merge 시나리오

1.  구글에서 https://git-school.github.io/visualizing-git/
2.  master라는 주어가 test를 합치고자 할때는 마스터로 이동해서 

```bash
$ git merge test
# merging이 master가 패스트포워드 머지를 하게되는데...
```

- 머지시나리오 중 브랜치중 하나의 브랜치에게만 커밋이 있을 경우 

3. 브랜치생성과 체크아웃을 동시에 하는 명령어

   ```bash
   $ git checkout -b test
   ```

4. ## Git merge 시나리오

   1. Fast Forward
   2. merge commit(w/o) conflict

   3. merge conflict

4. **fast-forward branch**
   * 어차피 포인터가 이동하는 방식이다. 
   * 두개를 합칠때 충돌이 난다면? 
   * 하나의 세계로 합쳐지는 느낌이 아니라, 전체가 다 보이는 느낌...?
   * `git`



:star:브랜치는 1회용이다. 

:star:브랜치는 재사용하지 않는다. 



## 브랜치 삭제

```bash
$ git branch -d test
```

## 

# 프로젝트소개

## 1. 프로젝트명

2. 



1. 프로젝트 소개