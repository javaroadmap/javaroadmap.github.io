---
layout: post
title:  "github file 사용 방법"
date:   2019-03-08 13:00:00 
categories: [github file]
---

지난 튜토리얼의 깃헙 폴더 생성에 이어서, 깃헙 파일 관리에 대해 학습을 한다. 관리할 깃헙 파일은 지난 튜토리얼에서 생성한 html5/basicHtml.html 이다. 깃헙에 로그인한 후, 저장소(jsptogo.github.io)에서 Code 탭을 클릭하고, 제시된 디랙토리 구조에서 html5 폴더를 클릭한다.
 
![Screen githubfile1](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubfile/githubfile1.png "Screen githubfile1")

html5 폴더를 클릭하면, 폴더 내에 저장된 파일이 제시되며, 현재 파일은 basicHtml.html 하나가 존재한다. 파일 관리화면으로 이동하기 위해,  basicHtml.html 파일명을 클릭한다.
 
![Screen githubfile2](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubfile/githubfile2.png "Screen githubfile2")

파일명을 클릭하면, 파일 관리화면이 제시된다. 관리화면에서 파일의 코드는 번호 리스트 형태로 제시되고, 오른쪽 중간에 보면 다수의 아이콘이 제공되는 것을 볼 수 있다. 이러한 아이콘 중에서 연필 아이콘은 파일 내용 수정에 관한 것이다. 파일 내용 수정을 위해 연필 아이콘을 클릭한다.
 
![Screen githubfile3](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubfile/githubfile3.png "Screen githubfile3")

연필 아이콘을 클릭하면, 소스코드 리스트 화면이 수정 가능한 형태로 변경되며, 이번 튜토리얼에서는 5번째줄의 타이틀을 '타이틀 표제'에서 '타이틀 표제를 여기에'로 수정해 보았다. 

![Screen githubfile4](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubfile/githubfile4.png "Screen githubfile4")

모든 수정이 진행되면, 화면을 아래로 스크롤하여 Commit changes(변경 커밋) 버튼을 클릭한다. 
 
![Screen githubfile5](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubfile/githubfile5.png "Screen githubfile5")

커밋 버튼이 클릭되면, 코드 편집 화면이 제시되고 코드가 조회된다. 5번째 줄이 변경된 것을 알 수 있다.
  
![Screen githubfile6](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubfile/githubfile6.png "Screen githubfile6")

https://jsptogo.github.io/html5/basicHtml.html 을 입력하고 웹 브라우저를 통해 확인해 보면, 아래 그림과 같이 타이틀이 변경된 것을 알 수 있다.

![Screen githubfile7](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubfile/githubfile7.png "Screen githubfile7")

이번에는 파일 및 폴더를 삭제해 보자. 이를 위해 저장소 초기 위치로 이동한 뒤, Code 탭을 클릭한다. 삭제할 대상은 html5 폴더이다. 이를 위해 html5 폴더를 클릭한다.

![Screen githubfile8](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubfile/githubfile8.png "Screen githubfile8")

html5 폴더 이름을 클릭하면, 폴더 내 파일 목록이 제시된다. 현재는 basicHtml.html 파일 하나만 존재한다. basicHtml.html 파일을  삭제하기 위헤 파일 이름을 클릭하여 관리화면으로 이동한다.
 
![Screen githubfile9](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubfile/githubfile9.png "Screen githubfile9")

basicHtml.html 관리화면에서 파일 삭제를 위해서는 쓰레기통 아이콘을 클릭하여야 한다. 
 
![Screen githubfile10](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubfile/githubfile10.png "Screen githubfile10")

쓰레기통 아이콘을 클릭하면, 확인 차원의 커밋 화면이 아래 그림과 같이 제시되며, 완전 삭제를 위해 아래쪽의 Commit changes(변경 커밋) 버튼을 클릭한다.
 
![Screen githubfile11](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubfile/githubfile11.png "Screen githubfile11")

변경커밋 버튼이 클릭되면, 이전의 html5 폴더 보다 한 단계 상위의 폴더인 루트 폴더 구조가 제시된다. 즉, 결과 화면에서는 html5 폴더가 삭제되었다. 이러한 이유는 기존 html5 폴더에 단 하나의 파일인 basicHtml.html 이 있었고, 해당 파일이 삭제되었으므로, 폴더가 더 이상 필요없다고 판단되어 깃헙은 폴더 html5 까지도 삭제한 것이다. 이러한 절차는  MS Windows 등 기존 OS에서의 폴더 관리 방법과는 다소 차이가 있는 점이며, 기존 OS에서는 파일이 없더라도 폴더 이름은 삭제하지 않는 반면에, 깃헙은 모든 파일이 삭제되어 없는 경우에 해당 폴더도 함께 삭제하는 것이다.    

![Screen githubfile12](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/githubfile/githubfile12.png "Screen githubfile12")

이제, 깃헙을 이용하여, 파일 및 폴더를 삭제할 수 있게 되었다.
