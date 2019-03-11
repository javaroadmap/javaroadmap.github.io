---
layout: post
title:  "github pages 사용 방법"
date:   2019-03-06 13:00:00 
categories: [github pages]
---
깃헙 페이지(GitHub Pages)는 깃헙 저장소를 이용하여 정적 웹 서비스를 제공하는 깃헙 서비스로 계정별로 서비스가 가능하다. 이번 튜토리얼에서는 깃헙 페이지 구축에 관해 학습한다.

사용자가 깃헙에 로그인 하면, 그림과 같이 대시보드 초기화면이 제시된다. 깃헙 시작을 위해 Start a project 버튼을 클릭한다.

![Screen github15](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubsignup/github15.png "Screen github15")

클릭 후에 신규 저장소(repository) 생성을 위한 화면이 아래 그림과 같이 제시된다. 신규 저장소를 생성하기 위해서 저장소 이름, 공개여부를 입력하고 Create repository 버튼을 클릭한다. 
본 튜토리얼에서는 깃헙 저장소가 홈페이지 역할을 수행하는 깃헙 페이지(GitHub Pages) 서비스를 이용할 예정이므로, 저장소의 이름을 본인의 '아이디이름.github.io'로 설정한다. 예를 들어, 튜토리얼에서 사용한 계정이 jsptogo 이므로, 저장소 이름은 jsptogo.github.io 가 된다. 저장소 이름의 중복이 없는 경우, 입력한 이름 욮에 체크 표시가 제시된다. 또한, 해당 사이트는 공개용으로 사용할 예정이므로  public 버튼을  체크하며 Initialize this repository with a README 항목은 체크하지 않는다. 설정이 끝난 후에, Create repository(저장소 생성) 버튼을 클릭한다. 

![Screen github16](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubsignup/github16.png "Screen github16")

저장소 생성 버튼을 클릭하면, 팝업 형태의 도움 메시지가 제시되며, 읽어본 후 Got it 버튼을 클릭하여 해당 팝업을 닫는다. 

![Screen github17](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubsignup/github17.png "Screen github17")

팝업을 닫으면, Quick setup 화면이 제시되며, 저장소 내에 새로운 파일을 생성하기 위해 중간 왼쪽의 create a new file(신규파일생성) 버튼을 클릭한다.
 
![Screen github18](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubsignup/github18.png "Screen github18")

신규파일생성 버튼을 클릭하면, 파일 이름, 파일 내용을 입력할 수 있는 화면이 아래 그림과 같이 제시된다.

![Screen github19](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubsignup/github19.png "Screen github19")

아래쪽 입력란에 파일 내용으로 아래의 소스 코드를 입력한다.  아래 예제는 HTML5, CSS3, 자바 스크립트가 모두 하나의 파일로 작성된 소스 코드이다.

![Screen github20](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubsignup/github20.png "Screen github20")

![Screen github21](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubsignup/github21.png "Screen github21")

내용을 입력한 후에는 아래 그림과 같이, 파일 이름으로 index.html을 입력한다.  

![Screen github22](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubsignup/github22.png "Screen github22")

파일 이름을 입력한 후, 스크롤을 아래쪽으로 이동하여, Commit new file(신규파일커밋) 버튼을 클릭한다.

![Screen github23](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubsignup/github23.png "Screen github23")

신규파일커밋 버튼이 클릭되면, 방금 입력한 index.html 파일 이름이 아래 그림과 같이 제시된다. 

![Screen github24](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubsignup/github24.png "Screen github24")

제시된 화면에서 index.html 파일을 클릭하면, 파일 내용 관련 수정, 삭제 등이 가능한 파일 관리화면으로 이동한다. 관리화면에서 이름 부분을 복사한다. 복사한 이름은 깃헙 페이지의 사이트 주소로 사용할 수 있다. 

![Screen github25](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubsignup/github25.png "Screen github25")

이제, 웹 브라우저를 새로 열기하고 복사한 사이트 주소를 입력하면, 해당 index.html 파일이 실행된다. 예제에서는 자바 스크립트가 그림과 같이 먼저 실행되며, 확인버튼을 클릭하여 팝업을 닫기한다. 

![Screen github26](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubsignup/github26.png "Screen github26")

팝업을 닫으면, HTML5와 CSS3로 구성된 메인 화면이 아래 그림과 같이 제시된다.
 
![Screen github27](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubsignup/github27.png "Screen github27")

이제, 깃헙을 이용한 홈페이지 구축이 완료되었다.
