---
layout: post
title:  "eclipse 설치 방법"
date:   2019-08-10 11:00:00 
categories: [eclipse]
---
 
이클립스(eclipse)는 윈도우스(windows), 맥OS(MacOS), 리눅스(Linux)등 다양한 소프트웨어 플랫폼에서 작동하는 
통합 개발 환경(IDE, Integrated Development Environments)으로 초기에는 자바 개발 환경으로 개발되었으나
최근에는 자바 프로그램을 포함하여, C/C++, PHP 등 매우 다양한 언어 환경을 지원한다.
 
이러한 확장성의 이면에는 이클립스 마켓 등을 통해 제공되고 있는 플러그인(Plug-in) 기능이 존재하고 있으며,
이클립스의 이용자 확대 및 활용성 증가에 큰 역할을 하고 있다.

2018년 현재 제공되고 있는 이클립스의 버전은 포톤(Photon)이며, 이클립스의 공식 홈페이지는 아래 그림과 같이 www.eclipse.org 이다.
홈 페이지에서 최신 버전을 다운로드 하기 위해서는 오른쪽 윗 부분의 주황색 Download 버튼을 클릭한다. 

![Screen eclipse1](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipseinstall/eclipse1.png "Screen eclipse1")

해당 버튼이 지정하는 위치는 https://www.eclipse.org/downloads/ 이며, 클릭 결과는 아래 그림과 같다.
이클립스를 설치하는 방법은 실행형과 패키지형으로 구분되는데, 이번 설명에서는 패키지형으로 진행한다. 즉, 왼쪽 아래 부분에 있는 Download Packages를 클릭한다.

![Screen eclipse2](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipseinstall/eclipse2.png "Screen eclipse2")
 
패키지 다운로드 화면에서는 다양한 버전의 이클립스를 제시하며, 현재 최신 버전은 2018-12월 버전이며, 'Eclipse IDE for Enterprise Java Developers'를 사용한다.  패키지의 사이즈는 334MB이고 343,909 번의 다운로드가 진행됬음을 알 수 있다.

사용자의 PC가 윈도우스 64 비트 운영체제를 사용하는 경우, 그림과 같이 Windows 64-bit를 클릭한다. 맥OS 및 리눅스의 경우도 패키지를 제공하고 있는 것을 볼 수 있다.

![Screen eclipse3](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipseinstall/eclipse3.png "Screen eclipse3")

패키지 다운로드를 위해서 eclipse-jee-2018-12-R-win32-x86_64.zip 파일을 클릭한다.

![Screen eclipse4](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipseinstall/eclipse4.png "Screen eclipse4")

다운로드에 대한 감사의 말이 제공되고, 크롬 브라우저의 경우 아래 바(Bar)에서 다운로드 진행사항을 볼 수 있다.

![Screen eclipse5](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipseinstall/eclipse5.png "Screen eclipse5")

다운로드가 완료된 후, 다운로드 바의 전체보기를 클릭하면 eclipse-jee-2018-12-R-win32-x86_64.zip 파일을 볼 수 있으며, 폴더 위치는 윈도우스 상에서 C:\users\USER\Downloads와 같다.

![Screen eclipse6](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipseinstall/eclipse6.png "Screen eclipse6")

다운로드 된 파일이 압축 파일이므로, 마우스를 파일위에 놓고 오른쪽마우스 클릭후 압출풀기 명령을 이용하여 해당 파일을 압축풀기(unzip) 해야 한다.

![Screen eclipse7](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipseinstall/eclipse7.png "Screen eclipse7")

압축 파일의 풀기 위치는 사용자의 선호 폴더에 자율적으로 실시할 수 있으며, 그림에서는 바탕화면의 jsptogo 폴더를 설치 위치로 선택하였다. 폴더를 선택한 후에, 압축풀기 버튼을 클릭한다.

![Screen eclipse8](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipseinstall/eclipse8.png "Screen eclipse8")
 
압축풀기 버튼을 클릭하면 팝업창의 형태로 패키지를 압축풀기하는 장면이 진행 정도를 포함하여 제공된다. 자세한 진행사항이 궁금한 경우 아래 자세히 버튼을 클릭하면 된다.
 
![Screen eclipse9](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipseinstall/eclipse9.png "Screen eclipse9")

압축풀기가 완료되면, 바탕화면의 jsptogo 폴더에 그림과 같이 6개의 서브 폴더와 각종 파일이 표시되며, 실행을 위해서 eclpise.exe 파일을 클릭한다.

![Screen eclipse10](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipseinstall/eclipse10.png "Screen eclipse10")

파일을 클릭하면 팝업창의 형태로 실행 확인 화면이 제공된다.  실행(R) 버튼을 클릭하여 실행한다.

![Screen eclipse11](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipseinstall/eclipse11.png "Screen eclipse11")
  
실행하면, 2018-12 버전 및 이클립스 로고가 그림과 같이 제시된다. 실행 파일 로딩 시간은 컴퓨터 사양에 따라 수십 초에서 수분의 시간이 소요된다.

![Screen eclipse12](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipseinstall/eclipse12.png "Screen eclipse12")

이클립스 로딩이 완료되면, Eclipse IDE Launcher 대화창이 제시되고 사용자가 작성할 내용이 저장될 작업폴더인 Workspace를 지정할 수 있다. 실행을 위해 Launcher를 클릭한다.

![Screen eclipse13](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipseinstall/eclipse13.png "Screen eclipse13")

팝업화면으로 Welcome(환영) 화면이 제시되고, 환영화면에서는 개요(overview), 튜토리얼(tutorials), 예제(samples), 새소식(what's new) 등 각종 정보 링크가 제공된다. 화면과 같이 X를 클릭하여 환영화면을 닫는다.
  
![Screen eclipse14](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipseinstall/eclipse14.png "Screen eclipse14")

환영화면을 닫으면 이클립스 초기화면이 제시된다. 초기화면은 윗쪽의 File, Edit, Navigate 등 툴바 부분, 왼쪽의 Project Explorer 등으로 구성된다. 

![Screen eclipse15](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipseinstall/eclipse15.png "Screen eclipse15")

이클립스를 이용한 개발에서 한글을 처리하기 위해서는 utf-8 설정이 필요하다. 한글 설정을 위해서 Window > Preferences > General > Appearance > Workspace로 이동한다. 그림과 같이 utf-8로 설정하고, Apply & Close 버튼을 클릭한다. 
 
![Screen eclipse16](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/eclipseinstall/eclipse16.png "Screen eclipse16")

이제, 이클립스를 이용한 코딩 개발이 준비되었다.
