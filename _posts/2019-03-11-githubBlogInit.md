---
title: GitHub 블로그 만들기를 위한 GitHub 블로그 포스트
---

# 1.블로그란? 

블로그는 웹(web)과 로그(log)의 합성어로 개인의 생각과 경험, 알리고 싶은 견해나 주장, 나아가 전문지식 등을 웹에다 일기(로그)처럼 기록해 다른 사람들도 보고 읽고 댓글을 달수 있게끔 열어 놓은 글모음을 말한다.
[네이버 지식백과] 블로그 [Blog] (손에 잡히는 IT 시사용어, 2008.02.01)<br>
~~용어 정리는 블로그의 필수?!~~

블로그 서비스를 이용할 수 있는 곳은 많이 있다.<br>
대표적으로 서비스형 블로그인 네이버블로그, 설치형 블로그인 Tistory, GitPage 가 있다.<br>

#### 서비스형 블로그 
1. 자신만의 주소를 가질 수 없다.
2. 디자인도 어느정도 주어진 범위내에서 선택적 사용을 해야한다.
3. 새로운 기능에 추가에 대해 신경 쓸 필요 없이 서비스 업데이트가 된다면 사용 할 수 있다.

#### 설치형 블로그 
1. 설치형 블로그의 경우 서비스형과 반대로 자유성이 매우 높다. 
2. 새로운 기능 추가에 대해 어려움이 있으므로 초보자라면 접근이 쉽지 않은 단점이 있다.

설치형 블로그 중 Git Page를 만드는 방법에 대해 알아보자.<br>
~~이 페이지도 Git Page로 만들어졌다.~~
# 2.GitPage 만들기
1. [깃허브 계정 만들기](https://github.com)
2.  Repository 생성
![image-center]({{ '/images/repository1.png' | absolute_url }}){: .align-center}
![image-center]({{ '/images/repository2.png' | absolute_url }}){: .align-center}
<span style="color:red">&#42;Repository이름과 GitPage의 이름은 동일해야 합니다.</span>
![image-center]({{ '/images/repository3.png' | absolute_url }}){: .align-center}
3. index.html 생성
* Index.html외에 Jekyll테마 적용시 index.md로 작성해야 하는 경우도 있습니다.
![image-center]({{ '/images/repository10.png' | absolute_url }}){: .align-center}
4. [username.github.io](https://bluenada08.github.io) 접속하면 index.html에 작성한 Hello World!가 보입니다.
![image-center]({{ '/images/repository11.png' | absolute_url }}){: .align-center}
5. 프로젝트관리를 위해 GIT을 연결해야 하는데 터미널에서  폴더로 이동 후 아래 명령어 입력하시면 됩니다.<br>
```
~ $ git clone https://github.com/username/username.github.io
```
6. 아래 명령어로 들어가 보시면 3번에서 만든 index.html이 들어와 있습니다.
```
~ $ cd username.github.io
```

*생각보다 GitPage만드는 방법은 간단합니다. 다음장에서 블로그 페이지 관리를 위한 Jekyll테마 적용에 대해 설명하겠습니다.