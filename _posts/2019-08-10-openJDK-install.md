---
layout: post
title:  "openJDK 설치 방법"
date:   2019-08-10 10:50:00 
categories: [eclipse]
---
 
SUN microsystems를 인수한 Oracle의 java 정책 변경에 따라 OpenJDK의 활용이 중요한 화두가 되었다.  openJDK의 공식 홈페이지는 아래 그림과 같이 adoptopenJDK.net 이다.
해당 홈 페이지에서 최신 버전을 다운로드 하기 위해서는 아래 방향으로 스크롤한다.

![Screen openJDK3](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/openJDKinstall/openjdk3.png "Screen openJDK3")

아래 그림과 같이 Other platforms 버튼을 클릭한다. 

![Screen openJDK4](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/openJDKinstall/openjdk4.png "Screen openJDK4")

2018년 현재 가능한 OpenJDK 11이며, 해당 버전을 클릭한 후, 아래로 스크롤한다.

![Screen openJDK5](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/openJDKinstall/openjdk5.png "Screen openJDK5")

금번 튜토리얼에서는 Windows 시스템에 openJDK를 설치할 예정이므로 Windows x64 아이콘을 그림과 같이 클릭한다.

![Screen openJDK6](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/openJDKinstall/openjdk6.png "Screen openJDK6")

JDK와 JRE 버전이 제시되며, 개발 목적으로 사용할 예정이므로  Download JDK를 아래 그림과 같이 클릭한다.

![Screen openJDK7](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/openJDKinstall/openjdk7.png "Screen openJDK7")

해당 파일의 다운로드가 진행된다. 다운로드가 완료될 때까지 대기한다.

![Screen openJDK8](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/openJDKinstall/openjdk8.png "Screen openJDK8")

Windows 탐색기를 오픈하여, 자바를 설치할 폴더를 확인한다. 금번 튜토리얼에서는 C 디렉토리 아래의 Program File > Java 폴더에 openJDK를 설치할 예정이다.  해당 폴더에는 아래 그림과 같이 기존에 사용되었던 JDK8 버전이 설치되어 있음을 알 수 있다. 

![Screen openJDK9](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/openJDKinstall/openjdk9.png "Screen openJDK9")

다운로드 받은 openJDK를 Java 폴더에 unzip 하면, 아래 그림과 같이 jdk-11-0.2-9 폴더가 생성된 것을 확인할 수 있다.  

![Screen openJDK10](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/openJDKinstall/openjdk10.png "Screen openJDK10")

jdk-11-0.2-9 폴더를 클릭하면 하부 폴더 구조를 아래 그림과 같이 확인할 수 있다. bin 폴더를 클릭하고, 해당 위치를 기억한다. 윈도우 Path 설정에 사용할 주소이다.    

![Screen openJDK11](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/openJDKinstall/openjdk11.png "Screen openJDK11")

이제, Windows 전반적으로 openJDK를 사용하기 위한 설정을 실시한다. 설정을 위해서는 컴퓨터(오른쪽마우스) > 속성을 선택한다.  Windows 10의 경우는 제어판 > 시스템및보안 > 시스템 > 고급시스템설정 > 환경변수를 선택한다.
 
![Screen openJDK12](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/openJDKinstall/openjdk12.png "Screen openJDK12")

현재 사용 중인 컴퓨터의  사양을 볼 수 있으며, 현재 PC는 인텔 i7, 메모리 8G, 64 비트 운영체제를 사용하고 있음을 알 수 있다.  
아래 그림과 같이 왼쪽의 고급시스템설정을 클릭한다.

![Screen openJDK13](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/openJDKinstall/openjdk13.png "Screen openJDK13")

환경변수 설정을 위한 시스템속성 화면이 제시되며, 고급 >환경변수를 아래 그림과 같이 클릭한다.

![Screen openJDK14](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/openJDKinstall/openjdk14.png "Screen openJDK14")

아래 부분의 시스템변수(S)의 Path를 클릭하고, 편집 버튼을 클릭한다.
 
![Screen openJDK15](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/openJDKinstall/openjdk15.png "Screen openJDK15")

클릭하면, 시스템 변수 편집 화면이 제시되며, 변수값의 마지막으로 이동하여, openJDK unzip 할 때 확인하였던 bin 폴더 위치를 설명과 같이 추가하고 확인버튼을 클릭한다.  

![Screen openJDK16](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/openJDKinstall/openjdk16.png "Screen openJDK16")

이제 Windows 환경에서 openJDK의 설치가 완료되었다.
JDK API 매뉴얼을 확인하기 위해서는 아래 그림과 같이 https://devdocs.io/openjdk~8 을 참조한다. 

![Screen openJDK17](https://raw.githubusercontent.com/javaroadmap/javaroadmap.github.io/master/static/img/_posts/openJDKinstall/openjdk17.png "Screen openJDK17")
