---
title: "⛏️ 메모 - Web 프로그래밍"
date: 2022-10-04. 10:03
categories: ⛏️Memo
---


## 💎 학교 수업 타자

---
Chapter 01 인터넷, Client, Server

1. Client-Server 환경

여러 대의 컴퓨터가 작업을 기능별로 분담하는 환경  
Computer : HW
System : HW + SW  
Client (System) : Server에 정보를 요청하는 시스템  
Server (System) : Client의 요청에 의해서 정보를 제공하는 시스템  

인터넷 연결된 컴퓨터 : Client or Server or Both

인터넷을 통해,  
Client는 자신이 지정한 Server로부터 정보를 요청 가능  
Server는 정보를 저장하고 있다가 정보를 요청한 Client에게 정보를 전달 가능  

Client-Server라고 하는 것은 좁은 의미로는 SW를 의미하는 것이 맞다고 볼 수 있습니다

---

2. Clinet-Server SW(프로그램)

Clinet SW -> Server SW

- Web Client -> Internet ->  Web Server
- FTP "
- Telnet "
- Email "

| 인터넷 서비스 | Client SW | Server SW |
| Web(world wide web) | Chrome, Edge, Safari, Internet Explorer | Apache, IIS(windowns), Sambar |
| e-mail | Outlook, Eudora, MailTrim | MDaemon, IceWarp, FTgate |
| FTP (File Transfer Protocol) | FileZilla Client FlingFTP, ClassicFTP |IIS(windows), serv-u, War FTP, FileZilla Server, WS FTP |
| Telnet | Pineterm, Winterm, Netterm, telnet Client(win 10) | telnet Server(win 10) telnet-server(Linux) |

인터넷을 통해 활용할 수 있는 서비스는 여러 가지  
각 서비스마다 사용하는 Client용, Server용 SW가 별도 있음
User가 각 서비스를 이용/제공하기 위해서는 그에 맞는 Client용 SW를 사용, Server용 SW도 설치, 동작시켜야 함  

Server용 SW들은 시스템 관리자들이 사용, 때문에 Client User는 Server 에 어떤 SW가 있는지는 몰라도 됨
원하는 서비스에 적합한 SW를 이용해 Server에 접속하기만 하면 됨

---

3. Web Client - Web Server

Web Clinet SW -> Web Server SW

- Chrome, Safari, Edge, Internet Explorer
- Internet
- Apache, IIS, Sambar ...

Web Client SW 를 일반적으로 Web Browser 라 부름

Client가 인터넷에 연결되어 있다고 해도 Web Browser가 설치되지 않으면 Web에 접속할 수 없음  
또한 Web Browser로 접속을 시도해도 지정한 Server 컴퓨터에 정보를 제공할 수 있는 Server SW가 실행되어 있지 않다면 Client에 정보를 제공할 수 없음  

Web SW가 Client/Server에 설치되면 User들이 Web서비스 이용 가능  
User는 Web Browser의 주소창에 자신이 원하는 사이트 주소를 입력하여 접속되면 원하는 정보를 Web Browser 화면으로 볼 수 있음

---

4. Web 개발 기술, Web 프로그래밍
Web 프로그래머 : Client, Server 기술 분야 프로그래머의 역할이 완벽히 분리되어 있지는 않지만, 기술을 구분하여 이해하고 있어야  

Web 서비스와 관련된 모든 파일들은 WebServer 시스템에 저장되어 있지만  

Front-end(Client Side Include) : HTML, CSS, Javascript 등의 파일  
User는 Web Browser를 통해 Web Server에 접속해서 정보를 가져옴  
Client HW에 다운로드 되고 Web Browser에서 실행됨  

모든 파일들을 Web Server에서 실행하게 하면 작업량이 몰리기 때문에 부하가 걸릴 수 있기 때문  

Back-end(Server Side Include) : PHP, JSP, ASP 등의 파일  
Server HW에서 실행되고 그 결과가 Web Browser에 전송  

---

Include : Program, Script : Program Code

--

4.1 Web Client 프로그래밍, Front-end, Client Side Include

Web Client 개발 : Front-end 또는 Client Side Include 개발  
주로 Web Browser에 정보를 보여주기 위해서 사용되는 기술들로 HTML(Hyper Text Markup Language), CSS(Cascading Style Sheet), Javascript 기술들  

HTML : Web 정보 또는 콘텐츠들을 잘 보여지게 위해 구조를 설정  
CSS : Web Browser에 정보 또는 콘텐츠들의 배치와 일관된 디자인과 관리를 하기 위한 기술
Javascript : 프로그래밍 언어, Web Browser에 보이는 정보들을 User의
반응에 따라 동적으로 보여지도록 하기 위해 (Popup 윈도우 생성, 메뉴구성, 화면전환효과, 버튼롤오버 등의 기능) 사용되는 기술, Front-end 개발의 핵심

VBScript 라는 것도 있지만 안쓰임

- 모든 소스코드들은 공개
- Client에서 처리되어 WebBrowser 실행되기 때문에 WebServer에 접속, 인터넷에 연결되어 있지 않아도 됨

---

4.2 Web Server 프로그래밍, Back-end, Server Side Include  

주로 데이터베이스와 연관  

- DB Data 삽입/수정/검색  
- 회원가입/로그인, 인증/보안, 정보/기능  

프로그래밍 언어로는 PHP(Professional Hypertext Preprocessor), JSP(Java Server Page), ASP(Active Server Page) 등  

Client에 코드가 전송되지 않기 때문에 보안유지 가능  
Web Server HW에서 실행되기 때문에 인터넷 연결 필요

---

4.3 Web Server System  
HW 켜져 있어도 SW가 실행되지 않게 되면 접속이 불가능  
SW로는 Apache, IIS(Internet Information Server), Sambar 등  

WebServer는 WebBrowser(Client)가 Web Site에 접속/정보 요청할 때 반드시 통과해야할 대문 같은 역할  

WebServer 관리자는 WebServer SW를 상황에 맞게 설정하여 WebSite 관리  

---
4.4 데이터베이스 관리시스템(DBMS : Data Base Management System)  

문서 짤림..

MariaDB vs MySQL

MySQL 핵심개발자들이 MySQL에 대한 오라클의 라이센스 정책이 자신들과 맞지 않는다
는 이유로 오라클사를 탈퇴해서 만든것이 MariaDB  
MariaDB는 MySQL의 소스코드를 그대로 사용하여 개발했기 때문에 모든 기능이 동일  
차이점은 라이센스 정책인데 MySQL은 소유권이 오라클에 있어서 기업에서 상업적으로 사용하는데 비용이 발생,  MariaDB는 오라클사와 무관하기 때문에 무료 사용이 가능합니다.(엔터프라이즈 버전은 유료지만 무료의 범위가 넓음)

---

Chapter 02 개발환경 구축

학기에는 PHP, Apache, DBMS는 MariaDB(MySQL)을 이용

1. [PHP](https://www.php.net)
1. [Apache](https://apache.org)
1. [MariaDB](https://mariadb.org)

개발도구들은 각각 별도로 설치할 수도 있지만 상호 연결을 설정하는 과정들이 복잡하기 때문에 이들을 한번에 설치할 수 있는 통합 개발환경(패키지)을 이용하여 구축합니다.

통합 패키지(Server 스택) : XAMPP (X(Cross) Apache MariaDB Php Perl), LAMP, MAMP, WAMP 등

4.1 [XAMPP (X(Cross) Apache MariaDB Php Perl)](https://www.apachefriends.org) :  

X(Cross)는 크로스 플랫폼을 의미하는 것으로 아키텍처가 동일한 컴퓨터(예를 들어 x86 아키텍처)에 설치된 다양한 운영체제(Windows, Linux, OS X)에서 문제없이 동작되는 프로그램 또는 소프트웨어  

XAMPP 통합 패키지는 가장 많이 사용되고 있는 PHP 프로그램 개발환경이며,  Control Panel(Server 통합관리 도구), phpMyAdmin(Web기반 DB 관리 도구) 등도 포함되어 있어 Web 개발에 편리성을 제공

PHP 기준으로 버전 업 (PHP 버전을 패키지 버전으로 사용)

4.2 LAMP/MAMP/WAMP

| 통합 패키지 | Server 스택 | 운영체체 |
| LAMP | Linux Apache MySQL Php | Linux 운영체제에서 동작 |
| MAMP | Mac Apache MySQL Php | Mac 운영체제에서 동작 |
| WAMP | Windows Apache MySQL | Php Windows 운영체제에서 동작 |

---

XAMPP Control Panel

Apache Web Server 구동 가능  
테스트 : 127.0.0.1 or localhost

Config에서 자동 시작 설정 가능 (XAMPP Control Panel 켜질 때 기준)  
Service 항목 체크 박스로 설정 가능 (컴퓨터 부팅 기준)  

주의 : CPU/Memory 사용, 외부 접속 허용

---

Apache Web Server

Apache Web Server 구성 파일 : httpd.conf  

구성 파일 : 시스템 관리나 인터넷 서비스 등에 필요한 구성을 설정해 놓는 일종의 환경 설정 파일

httpd의 d : daemon :  
악령 또는 그리스 신화에서 초자연적인 존재 :  
User가 직접 제어하지 않고, 백그라운드에서 돌며 작업을 하는 프로그램 = 상주 프로그램 (resident program)

MySQL도 mysqld 이름으로 백그라운드 작업 목록에 등록되어 수행

여러 가지 환경을 기본값으로 미리 설정됨  
Web사이트의 운영 환경에 맞게 변경 즉 재설정 : XAMPP의 기본 설정은 공개된 정보이기 때문에 외부에서의 해킹 등으로 문제가 될 수 있음

httpd.conf 파일 백업해두면 좋음  
C:\xampp\apache\confhttpd.conf  
XAMPP Control Panel의 [Config] 통해서도 쉽게 불러올 수 있음  

8.1.6 버전 566 라인 기준  
&#35; 주석  
내용 변경 후 재시작해야 적용  

---

2. WebServer 루트 폴더 및 초기 파일  

Web Browser에 사이트 주소만를 입력하여 접속을 요청하면  
Web Server는 홈페이지의 시작 내용 : 메인 페이지 : 초기 파일을 전송  

XAMPP 루트 폴더 : 초기 파일과 이름이 저장된 폴더 :  
C:\xampp\htdocs\index.php  

루트 폴더 이름, 경로, 초기 파일 이름 재설정 가능

2.1 Web사이트 초기 파일 이름 변경  

DirectoryIndex 단어로 검색  
DirectoryIndex 단어 뒤에 초기 파일 나열 (index.php index.pl index.cgi 등)  
루트 폴더에 저장되어야 함  

Web 사이트에 Browser로 접속하면 Web Server는 루트 폴더로 이동하여 나열된 파일이 있는지 확인, 있으면 파일 or 처리결과 전송 (Client Side면 파일, Server Side면 처리결과 전송)

```conf
<IfModule dir_module>
    DirectoryIndex index.php index.pl index.cgi index.asp index.shtml index.html index.htm \
                default.php default.pl default.cgi default.asp default.shtml default.html default.htm \
                home.php home.pl home.cgi home.asp home.shtml home.html home.htm
</IfModule>
```

나열된 파일 이름들은 Web 관리자만 알고 있는 내용  

초기 파일이 필요한 이유는 사이트 주소만 입력해도 홈페이지의 내용을 확인할 수 있도록하기 위해서입니다.  
즉 사이트 주소 예를 들어 <http://naver.com> 주소만 입력해도 홈페이지의 내용이 보이는 이유는 등록된 초기 파일이 동작하기 때문입니다.  
이렇게 하면 초기 파일의 이름을 외부에서 알 수 없도록 할 수 있습니다.  

Web Browser에서 127.0.0.1 또는 localhost 접속하면 index.php 파일이 실행  
127.0.0.1/index.php

임의의 파일을 만들어 루프 폴더에 저장하고 초기 파일 이름을 수정하면,  
Web 사이트 접속 시 해당 파일로 접속  
외부에서는 알 수 없음.  

---

2.2 WebServer 루트 폴더 재설정

루트 폴더는 해당 사이트의 모든 홈페이지 관련 파일 저장  
기본 값은 공개된 정보이기 때문에 보안을 위해 변경하여 재설정 필요  

DocumentRoot 단어로 검색

```conf
DocumentRoot "C:/xampp/htdocs"
<Directory "C:/xampp/htdocs">
:
:
</Directory>
```

경로를 변경해도 외부에서는 알 수 없음  
드라이브도 변경 가능  

Web사이트 초기 파일 설정의 에서 목록에 나열된 초기 파일이 없을 경우  
루트 폴더에 저장되어 있는 모든 파일들의 목록이 표시됨  

디렉토리 인텍싱(Directory Indexing) :
루트 폴더, 하위 폴더, 파일 목록을 제공하는 것은 보안에 매우 취약  

Require all granted 문장 : 디렉토리(폴더) 목록표시를 허용

granted를 denied으로 변경하거나  

# 을 이용해 주석 처리  

Forbidden 메시지가 표시되면서 파일 목록을 확인할 수 없게 됨

---

2.3 포트 설정

인터넷 서비스들은 하나의 Server시스템에 설치되어 동작될 수 있고, 또 실제로도 그렇게 운영하고 있음  

하나의 컴퓨터에 여러 개의 Server 소프트웨어들을 설치하여 인터넷 서비스들을 제공할수 있음

그렇다면 인터넷 회선 하나로 여러 개의 서비스 즉 여러 개의 Server들에 접속할 수 있을까?  

케이블 TV는 하나의 회선으로 많은 채널을 통해 방송 콘텐츠를 제공  
User는 원하는 방송 콘텐츠를 보기 위해 채널을 선택  

인터넷 서비스들도 유사한 방식으로 접속  
컴퓨터에는 인터넷 연결을 위해 회선 대신 네트워크 카드  
이 네트워크 카드는 컴퓨터에 설치된 여러 Server에 접속될 수 있도록 포트(port)라는 것이 있고, 이 포트가 케이블 TV의 채널과 비슷한 역할  

User가 Web서비스를 이용하려면 Web포트에 접속되고, FTP 서비스를 이용하려면 FTP 포트에 접속  
포트의 개수는 총 16비트, 65,536개(0~65,535) 정도  
이중에서 Web, FTP, Telnet, E-mail 등의 인터넷 서비스를 위해 미리 할당됨 (시스템 포트).  

| 인터넷 서비스 | Web | FTP | Telnet | E-mail |
| 포트 번호 | 80 | 21 | 23 | 25 |

이 번호를 Web 주소 뒤에 콜론과 함께 :80을 추가하여 127.0.0.1:80 형태로 해도 접속이 됩니다. = 127.0.0.1로 접속하는 것과 같습니다.  

Web 포트를 재설정  
httpd.conf 에서 Listen 검색  
포트를 사용해서 접속하는 방법을 나타내는 주석문  
다음 라인에 80 이라는 Web 기본 포트를 원하는 포트 번호로 변경  

8080으로 재설정  
127.0.0.1로 접속하면 접속되지 않음  
Web 포트를 8080으로 재설정했기 때문에 127.0.0.1:8080 접속 가능  

Listen 라인을 하나 더 추가하면 2개의 포트번호로 모두 접속이 가능  

Web 포트 번호를 재설정해야 이유는 다양  
Web Server를 관리하다 보면 이렇게 해야 하는 경우가 종종 발생  

---

Chapter 04 PHP 동작의 이해

1. PHP 역사
PHP는 덴마크계 캐나다인 라스무스 러도프(Rasmus Lerdorf)가 1995년에 만든 것으로, 간편하게 Web사이트를 작성하기위해 개발  
1995년 PHP 1.0 버전을 시작으로 개발이 계속되어 8.1.7 버전에 이름  

처음에는 Personal HomePage tools의 줄임말이었는데, 현재는 Personal Hypertext Preprocessor로 사용  

tiobe.com 사이트에서는 사용 비율에 대한 순위 정보를 매달 제공하고 있는데, PHP 10위권 내외에서 사용되고 있음

2. PHP 특징

PHP는 Web사이트를 제작하기 위해 만들어진 언어로써 HTML/CSS와 함께 사용  
PHP 언어처럼 Web사이트를 제작하는 언어 :  
ASP(Active Server Page) : MS사 언어인 BASIC을 기반, MS사의 IIS(Internet Information Service)라는 Web Server에서만 동작  
JSP : Java 언어를 기반, Java의 모든 기능을 사용 가능  

보통 PHP는 중소 규모의 Web사이트 개발에 적합하고, JSP는 대규모 Web사이트 개발에 적합  
또한 PHP의 경우 연동되는 (Linux, Apache, MySQL)들이 무료이기 때문에 개발 및 비용은 ASP, JSP에 비해 저렴하다고 합니다.
다음의 표는 각 언어들의 최적화된 환경을 제시했지만 운영 상황에 따라서 다를 수도 있으니 참고만 하기 바랍니다.

| 언어 | 운영체제 | WebServer | DBMS |
| PHP | MS Windows, Linux, MacOS | Apache | MySQL |
| ASP | MS Windows | IIS | MSSQL |
| JSP | MS Windows, Linux, MacOS | Apache Tomcat | Oracle |

PHP 특징  

- C 기반
- PHP 엔진 : 오픈소스, 무료
- PHP 엔진 : 다양한 HW와 OS에서 사용되며 플랫폼 독립적
- 동작 속도가 빠르고 성능이 좋은 편, 접속자가 많아도 사이트 운영에 큰 문제가 없음

3. PHP Web 프로그램 처리 과정

PHP는 WebServer를 통해서만 실행 가능, DBMS와 연동해서 동작  

- Client System 에서 인터넷을 통해 Server System에 처리 요청
- PHP 프로그램에서 처리
- PHP 엔진에서 코드 해석 (해석기)
- DBMS
- DB
- Server System 에서 인터넷을 통해 Client System에 에 처리 결과 전송

4.1 PHP 프로그램 작성

```php
<?php
echo "<h2>Hello World</h2>";
?>
```

4.2 PHP 프로그램 실행

반드시 WebServer가 동작중인 상태에서, WebBrowser를 이용해 PHP 프로그램을 실행해야 함  
윈도우 탐색기에서 php 파일을 더블클릭하는 것은 PHP 프로그램의 실행이 아님  

127.0.0.1/phptest/first.php

4.3.1 PHP 프로그램 파일의 확장자

동일한 소스코드의 내용을 확장만 .php .html 로 달리해서 저장  
이를 WebBrowser를 이용하여 접속 요청하면 그 결과가 WebBrowser에 표시  

확장자가 .php인 파일은 PHP 엔진이 PHP 언어의 문법에 맞게 해석하고 WebBrowser에 처리 결과만 전달  
파일에서 <?php ... ?> 부분을 PHP 엔진이 처리하여 결과인 <h2>...</h2> 코드만을 WebBrowser에 전달  
echo 명령문은 인용부호에 들어있는 내용을 WebBrowser에 그대로 전달하는 기능  

php 코드가 포함된 파일들은 반드시 .php 확장자로 관리  

4.3.2 HTML 구조에서 PHP 코드

페이지 소스보기를 하면 곱하기 하는 수식은 나타나지 않고 곱하기 결과만 출력됩니다.

HTMl 구조 내의 PHP 코드
<?php
$op1 = 123; $op2 = 456;
$multi = $op1 * $op2;
echo "$op1, $op2 곱하기 결과 : $multi";
?>

WebBrowser 출력, 페이지 소스보기
123, 456 곱하기 결과 : 56088

HTML 구조 내의 PHP 코드는 구조상 <body>와 </body> 사이에 작성하는 것이 좋음  

PHP 코드 안의 HTML 코드
<?php
$op1 = 123; $op2 = 456;
$multi = $op1 * $op2;
echo "<i>";
echo "$op1, $op2 곱하기 결과 : $multi";
?>

WebBrowser 출력
123, 456 곱하기 결과 : 56088

페이지 소스보기
<i>123, 456 곱하기 결과 : 56088

---

PHP

PHP 기본 구조  

```php
<?php ?>

<? ?>
```

<? ?> 으로 사용하려면 설정 필요  
Web Server 처럼 PHP도 환경 설정 가능  
\xampp\php\php.ini  
short_open_tag = 설정 값 (default : Off, On)  
다른 언어들의 기호와 충돌이 있을 수 있기에 기본값인 Off 로 해두는 것이 좋음  

// 주석  
&#35;  주석  
/**/ 주석  

PHP 키워드인  
<?php, echo, if, print 등은  
<?PHP, ECHO, IF, PRINT 와 같음  

사용자가 정의한 변수명, 상수명은 대소문자를 구분 (Case Sensitive)  
사용자가 정의한 함수명은 대소문자를 구분하지 않음 (Case Insensitive)

PHP 변수 선언  
$ 기호 이용  

출력  
echo  

- 문자열, 변수, 상수 값 출력  
- HTML 태그를 포함하여 Web Browser에 전송  
- echo문은 여러 개의 인수를 출력할 수 있음  

1) 문자열, HTML 태그, &nbsp; 기호 출력  
echo "Hello World";  
echo 'Hello World';  

2) 변수 출력  
변수명으로만 출력 가능  
echo $temp;  
echo "$temp";  
echo ($temp);  
echo "{$temp} Hello";

3) 여러 인수 출력  
echo $temp, "Hello";  
// 인수 나열 연산자  
echo $temp. "Hello";  
// 문자열 결합 연산자  

print  
인수 1개만 사용 가능, 괄호 사용 X  

printf  
C 랑 같음, Formatted String  
printf("%%d = '%d'", $temp);  

---

변수명 : lvalue : 메모리 주소 : Reference 참조  

메모리 주소와 용량  
메모리 주소는 편의상 16진수로 표현  
16진수 첫 자리는 2^4 = 16B, 두 자리는 2^8 = 256B, 여덟 자리는 2^32 = 4MB

arr = [1, 2, 3]; // 배열
temp = object {
    name : 'TEMP',
    addr : 'TEMP'
}
add = func(a, b){
    sum = a + b;
}

PHP 에서의 배열 복사는 깊은 복사
얕은 복사를 원한다면 명시적으로 & 기호 표기

객체 복사는 얕은 복사

느슨한 (loosy) 데이터 타입
PHP 변수는 미리 선언할 필요가 없으며, 데이터 타입도 정의할 필요가 없음

데이터에 기반한 데이터 타입의 자동 설정  
수시로 저장되는 데이터 타입에 따라 변수의 데이터 타입 결정

is_타입

var_dump  변수 정보 출력  
gettype()  
settype()  

미리 정의된 변수

Super Global Variables

- $GLOGALS : 전역 범위에서 사용되는 모든 변수들을 참조
- $_SERVER : 서버 정보 및 실행 시 발생되는 환경 정보들을 참조
- $_GET : HTTP GET 방식에 사용되는 변수들을 참조
- $_POST : HTTP POST 방식에 사용되는 변수들을 참조
- $_FILES : HTTP 업로드 시 파일 변수들을 참조
- $_REQUEST : HTTP 요청 시 발생되는 정보들을 참조
- $_SESSION : 세션 처리 시 사용되는 변수들을 참조
- $_ENV : PHP 파서 동작시 발생하는 환경 변수들을 참조
- $_COOKIE : 쿠키 처리 시 사용되는 변수들을 참조

일반 기정의 변수

- $http_response_header : HTTP 응답 헤더 정보들을 참조
- $argc : 커맨드 라인 환경에서 argument 개수 반환
- $argv : 커맨드 라인 환경에서 argument 명칭을 배열로 반환

상수 const  

핵심 상수
PHP 엔진이 설치되면서 시스템과 연관된 정보들을 값으로 보관하는 PHP 모듈 상수

핵심 상수 일부

- PHP_VERSION : 설치된 PHP 버전을 나타내는 상수
- PHP_OS : 운영체제를 나타내는 상수
- PHP_OS_FAMILY : 세부 운영제체를 나타내는 상수
- PHP_MAXPATHLEN : 경로가 포함된 파일이름의 최대 길이를 나타내는 상수
- PHP_INT_SIZE : 정수의 크기를 바이트 단위로 나타내는 상수

매직 상수

컴파일 또는 실행할 때 발생되는 값이며, 어떤 코드를 언제 실행했는냐에 따라
다른 값을 나타냅니다.  

매직 상수 일부

- __LINE__ : 파일 내에서 현재 라인번호를 나타내는 상수
- __DIR__ : 파일명을 포함하고 있는 폴더명을 나타내는 상수
- __FILE__ : 폴더를 포함한 파일명을 나타내는 상수

bool  
false == FALSE == "", "0", 0, 0.0, NULL, 원소 없는 배열  
true == TRUE == 나머지  

int  
OS 32비트, 64비트에 따라 다름

PHP_INT_SIZE  
PHP_INT_MIN  
PHP_INT_MAX  
number_format()

float 8Byte  

string 문자 한 개 1Byte  
최대 길이 OS 32비트 = 2^32, 64비트 무제한  

** 거듭제곱 연산자  

. 문자열 연결 연산자  

=== 데이터 타입이 같은지  

<>  == !=  

!== 데이터 타입 다른지

<=> 크면 1 같으면 0 작으면 -1  

echo ($a == $b)."<br>";  
echo ($a != $b)."<br>";//false 면 출력되지 않음  
echo ($a === $b)."<br>";//false 면 출력되지 않음  
echo ($a !== $b)."<br>"  

and or xor  
우선 순위 = 보다 낮음  

실행 연산자(Execution Operators)
` : 쉘 명령어를 웹브라우저에서 실행, shell_exec() 함수와 동일한 기능

$output = `dir`;  
echo "<pre>$output</pre>";

$output = shell_exec(`dir`;);  
echo "<pre>$output</pre>"

while () { /.../ }  
while (): endwhile;  

for () { /.../ }  
for (): endfor;  

foreach (반복구조 as $value) { /.../ }  
foreach (반복구조 as $Key => $value) { /.../ }  
Key 인덱스, value 요소  
value 값 바꿔도 원래 배열에는 기본적으로 반영 X  
변경하려면 조건문에 & 기호 사용 (&$value)  

함수  
function 키워드 이용

Formal Parameter 매개변수, 형식인자 함수 정의에 사용되는 변수명  
Actual Argument 실인자(인수), 전달인자(인수), 전달값 함수 호출에 사용되는 실제값  

배열  
Index로 숫자, 문자열 사용  
Index가 문자열이면 연관 배열 Associative Array 라고 함  

$arr = array( , , );
$arr = [ , , ];

$arr = array(" " => , " " => , );  
$arr = [" " => , " " => , ];  

print_r  
배열 특정 요소, 배열 전체 요소 출력  
echo는 배열 전체 요소 출력이 불가능  

객체 속성과 메소드 사용을 위해 -> 기호 사용  

3. 수치 함수  
3.1 수학 함수 일부

| float sin(float $num) | 사인 |
| float cos(float $num) | 코사인 |
| float tan(float $num) | 탄젠트 |
| float exp(float $num) | e 지수값 |
| float log(float $num) | 자연 로그값  |
| float log10(float $num) | 상용 로그값 |
| int\|float abs(int\|float $num) | 절대값 |
| float pi() | Pi |
| float rad2deg(float $num) | 라디언의 각도값 |
| float deg2rad(float $num) | 각도의 라디언값 |
| float sqrt(float $num) | 제곱근 |

| float ceil(int\|float $num) | 올림 정수값 |
| float floor(int\|float $num) | 내림 정수값 |
| float round(int\|float $num, int $precision) | 반올림 |

| mixed min(mixed $value, mixed ...$values) | 최소값 |
| mixed max(mixed $value, mixed ...$values) | 최대값 |

배열 인수로 사용 가능

| string decbin(int $num) | 10진수 -> 2진수 |
| string decoct(int $num) | 10진수 -> 8진수 |
| string dechex(int $num) | 10진수 -> 16진수 |
| int\|float bindec(string $binary_string) | 2진수 문자열\|숫자 -> 10진수 |
| int\|float octdec(string $octal_string) | 8진수 문자열\|숫자 -> 10진수 |
| int\|float hexdec(string $hex_string) | 16진수 문자열 -> 10진수 |

| string number_format(float $num, 소수점자리수, 소수점기호, 천단위기호):

| string chr($ascii_num) | 10진수 -> Char |
| int ord(string $character) | Char -> ASCII(10진수) |
| string nl2br(string $string)  | "\n" -> \<br\> (Newline To br) |
| array explode(string $separator, string $string) | Split |
| string implode(string $separator, array $array) | Join() |
| int strlen(string $string) | 문자열 길이 (바이트 단위) |

| time() | 1970/01/01 누적된 초 |
| string date(string $format) | |

| c | 2022-07-18T12:17:31+02:00 |
| r | Mon, 18 Jul 2022 12:17:31 +0200 |
| Y | 연도 | 1999, 2022 |
| y | 연도 | 01, 22 |
| F | 월 | January ~ December |
| m | 월 | 01 ~ 12 |
| n | 월 | 1 ~ 12 |
| M | 월 | Jan ~ Dec |
| t | 월 일수 | 28 ~ 31 |
| d | 날짜 | 01 ~ 31 |
| j | 날짜 | 1 ~ 31 |
| D | 요일 | Mon ~ Sun |
| l | 요일 | Monday ~ Sunday |
| N | 요일 | 1 ~ 7 |
| w | 요일 | 0 ~ 6 |
| a | 오전, 오후 | am, pm |
| A | 오전, 오후 | AM, PM |
| g | 시간 | 1 ~ 12 |
| G | 시간 | 0 ~ 23 |
| h | 시간 | 01 ~ 12 |
| H | 시간 | 00 ~ 23 |
| i | 분 | 00 ~ 59 |
| s | 초 | 00 ~ 59 |

| resource opendir($dir) | 경로 열어 시스템 자원으로 |
| string readdir($dir_handle) | 지정된 시스템 자원에서 파일 목록을 문자열로 반환 |
| bool closedir($dir_handle) | 지정된 시스템 자원의 디렉터리를 닫음 |

readdir : 파일 목록 차례로 가져오는

| array scandir($dir) | 시스템 자원에서 디렉터리(파일) 목록 |
| array scandir($dir, 1) | 내림차순 정렬 |

| bool is_dir($dir) | 디렉터리? |
| bool mkdir($dir) | 디렉터리 생성 |
| bool rmdir($dir) | 디렉터리 삭제 |

| resource fopen($filename, $mode) | 파일을 열어 시스템 자원으로 |
| bool fclose($file_handle) | 지정된 시스템 자원의 파일을 닫음 |
| int filesize($filename) | 파일의 크기(바이트 수) |
| bool is_file($filename) | 파일? |
| bool file_exists($filename) | 파일\|디렉터리? |

fopen 함수의 $mode 옵션  

| r | 읽기 전용 | 읽기 위치(파일포인터)는 파일의 처음. 파일이 없으면 에러 |
| r+ | 읽기/쓰기 | 읽기/쓰기 위치(파일포인터)는 파일의 처음. 파일이 없으면 에러 |
| w | 쓰기 전용 | 파일이 있으면 내용을 삭제하고, 없으면 새 파일 생성 |
| w+ | 읽기/쓰기 | 파일이 있으면 내용을 삭제하고, 없으면 새 파일 생성 |
| a | 추가 전용 | 추가 위치(파일포인터)는 파일의 끝. 파일이 없으면 새 파일 생성 |
| a+ | 읽기/추가 | 읽기/추가 위치(파일포인터)는 파일의 끝. 파일이 없으면 새 파일 생성 |
| x | 쓰기 전용으로 생성 | 파일이 있으면 에러, 없을 때 새 파일 생성 |
| x+ | 읽기/쓰기용으로 생성 | 파일이 있으면 에러, 없을 때 새 파일 생성 |

파일 내용을 읽기 위해서는 fopen 옵션 r r+  

| string fread($file_handle, $length) | 정보를 이용하여 $length 바이트 만큼 문자를 읽음 |
| string fgetc($file_handle) | 파일 포인터에서 문자 단위로 읽음 |
| string fgets($file_handle) | 파일 포인터에서 라인 단위로 읽음 |

파일 내용을 쓰기 위해서는 fopen 옵션 w w+ a a+ x x+  

| int fwrite($file_handle, $string) | $file_handle 정보를 이용하여 $string 문자열을 쓰기 |
