---
layout: post
title:  "이클립스 자바 설정 방법"
date:   2019-08-13 13:50:00 
categories: [eclipse]
---
 
이클립스에서 자바를 사용하기 위해서는 이미 설치된 자바 프로그램의 환경을 설정하여야 한다.
이를 위해서는 Window > Preferences > Java > Installed JREs 로 이동한다. 그림과 같이 Add 버튼을 클릭한다. 
  
![Screen eclipsejava1](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava1.png "Screen eclipsejava1")

클릭후 제시되는 화면에서 Standard VM을 선택한 후, Next 버튼을 클릭한다.
![Screen eclipsejava2](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava2.png "Screen eclipsejava2")

Add JRE 화면이 제시되며, JRE home의 Directory 버튼을 클릭한다.
![Screen eclipsejava3](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava3.png "Screen eclipsejava3")

제시된 JRE 중에서, 금번 튜토리얼에서는 openJDK를 사용할 예정이므로, 첫번째 jdk-11.0.2를 check히고 아래쪽의 Applu and Close 버튼을 클릭한다. 
![Screen eclipsejava4](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava4.png "Screen eclipsejava4")

이제 자바 설정이 완료되었으므로, 예시를 통해 자바 프로그램을 이클립스에서 실행해 보자.
이클립스 화면에서  File > New > Project 를 그림과 같이 순서대로 클릭한다.
 
![Screen eclipsejava5](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava5.png "Screen eclipsejava5")

클릭후, New Project 화면창이 제시되며, 자바 프로젝트를 실행할 예정이므로, Java Project 를 선택하고 Next 버튼을 클릭한다.
 
![Screen eclipsejava6](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava6.png "Screen eclipsejava6")

클릭후, New Java Project 화면이 제시되며, Project name에 javaro (임의로 선호하는 이름을 입력)를 입력하고, JRE 부분 JavaSE-11을 선택한 후, Next 버튼을 클릭한다.
 
![Screen eclipsejava7](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava7.png "Screen eclipsejava7")

javaro 이름을 확인한 후, 아래 그림과 같이 Finish를 클릭한다.

![Screen eclipsejava8](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava8.png "Screen eclipsejava8")

finish 클릭 후, New module-info.java 화면이 제시된다.  해당 파일의 생성을 원하지 않으므로, Don't Create 버튼을 클릭한다.

![Screen eclipsejava9](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava9.png "Screen eclipsejava9")

자바 Perspective에 대한 대화창이 제시된다. 이 부분으 필요하므로, Open Perspectㅑve를 클릭한다.
이제 javaro 프로젝트가 생성되었다.

![Screen eclipsejava10](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava10.png "Screen eclipsejava10")

자바 프로그램은 패키지를 기준으로 관리되므로, 생성된 javaro 프로젝트에 새로운 패키지를 설치하여야 한다. 이르 위해서는 javaro > src > New > Package를 순서대로 클릭한다. 

![Screen eclipsejava11](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava11.png "Screen eclipsejava11")

클릭 후, New Java Package 화면이 제시되며, Source folder를 확인하고, Name 부분에 org.javaro.mybookstore를 입력한다. 패키지 이름은 사용자 임의로 작성한다.

![Screen eclipsejava12](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava12.png "Screen eclipsejava12")

패키지 이름이 설정되었으므로, .java로 정의되는 자바 소스 파일을 작성할 차례이다.  이를 위해서는 org.javaro.mybookstore 패키지 이름에 마우스를 위치하고 오른쪽 마우스를 클릭한다. New > Class 를 차례대로 클릭한다. 

![Screen eclipsejava13](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava13.png "Screen eclipsejava13")

클릭 후, New Java Class 화면이 제시되며, Source folder 및 Package 이름을 확인하 후, 작성하고자 하는 자바 파일 이름이 Ex.java인 경우, Name 부분에 Ex 만 입력한다. Ex.java를 모두 입력시 오류가 발생하며, 자바 파일이름은 첫누자를 대문자로 사용하므로 이를 확인하다.  Finish 버튼을 클릭한다.

![Screen eclipsejava14](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava14.png "Screen eclipsejava14")

테스트할 코드는 간단하게 문자열을 화면 인쇄하는 프로그램이다. 

![Screen eclipsejava15](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava15.png "Screen eclipsejava15")

화면 왼쪽에 EX.java를 클릭하고, 소스 코드를 그림과 같이 입력한다.
 
![Screen eclipsejava16](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava16.png "Screen eclipsejava16")

코드 오류를 모두 바로 잡고, 실행한다. 이를 위해서는 상단의 초록색 오른쪽화살표를 클릭하거나, 아래쪽 검은색 화살표를 클릭하고 Run As > 1 Java Application을 연속으로 클릭한다.
 
![Screen eclipsejava17](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava17.png "Screen eclipsejava17")

Save and Launch 대화창이 제시되는 경우, Ex.java 파일을 선택하고 OK 버튼을 클릭한다.

![Screen eclipsejava18](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava18.png "Screen eclipsejava18")

실행결과가 화면 아래 Console 부분에 제시된다. 금번 프로그램에서는 2학년 홍길동이 제시되었다.

![Screen eclipsejava19](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava19.png "Screen eclipsejava19")

다음 그림은 참고용으로 온라인에서 자바 프로그램 실행할 수 있는 https://repl.it/languages/java 사이트이다. 

![Screen eclipsejava20](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava20.png "Screen eclipsejava20")

다음 4개 그림은 참고용으로 이클립스에서 자동탭의 크기를 조정하는 화면이다. 

![Screen eclipsejava21](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava21.png "Screen eclipsejava21")

![Screen eclipsejava22](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava22.png "Screen eclipsejava22")

![Screen eclipsejava23](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava23.png "Screen eclipsejava23")

![Screen eclipsejava24](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava24.png "Screen eclipsejava24")

다음 8개 그림은 참고용으로 이클립스에 자바 jar 라이브러리를 포함하는 화면에 관한 것이다. 

![Screen eclipsejava25](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava25.png "Screen eclipsejava25")

![Screen eclipsejava26](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava26.png "Screen eclipsejava26")

![Screen eclipsejava27](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava27.png "Screen eclipsejava27")

![Screen eclipsejava28](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava28.png "Screen eclipsejava28")

![Screen eclipsejava29](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava29.png "Screen eclipsejava29")

![Screen eclipsejava30](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava30.png "Screen eclipsejava30")

![Screen eclipsejava31](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava31.png "Screen eclipsejava31")

![Screen eclipsejava32](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipsejava/eclipsejava32.png "Screen eclipsejava32")

