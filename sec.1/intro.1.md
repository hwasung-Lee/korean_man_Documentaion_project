# 이름
설명서 - 사용자 명령어에 대한 설명들

# 설명
본 매뉴얼의 섹션1은 파일 처리 도구, 쉘, 컴파일러, 웹브라우저 등 사용자 명령어나 도구들에 대해서 설명합니다.

# 추가 설명
리눅스는 UNIX 계열 운영체제이고, UNIX에서의 모든 유저 명령들이 처음으로 리눅스에서 작동합니다.(그리고 FreeBSD 그리고 수많은 다른 UNIX계열 운영체제들에서도).

## 로그인
작업을 시작하기 위해, 여러분은 아마 아이디(유저 네임)와 비밀번호를 넣어 새로운 세션을 열어야 할 것 입니다. 프로그램 **login(1)**가 이제 당신을 위해 쉘(명령 처리기)를 시작해 줄 것입니다. GUI데스크톱 환경을 통한 로그인의 경우, 여러분은 메뉴를 받거나 아이콘들과 마우스 클릭이 창에서의 쉘을 시작할 것 입니다. **xterm(1)**을 참고하세요.

## 쉘
누군가 명령어를 쉘(명령 처리기라고도 함)에 입력합니다. 이것은 내장되어 있는 것이 아니지만, 그저 프로그램일뿐이고, 당신은 당신의 쉘을 변경할 수 있습니다. 모든 사람들은 모두 자신만의 최애 쉘이 있습니다. 가장 표준적인 쉘은 'sh'입니다. 다음을 참고하세요: **ash(1)**, **bash(1)**, **chsh(1)**, **csh(1)**, **dash(1)**, **ksh(1)**, **zsh(1)**

이렇게 실행되고 있는 세션이 있습니다:
```
knuth login: aeb
Password: ********
$ date
Tue Aug  6 23:50:44 CEST 2002
$ cal
     August 2002
Su Mo Tu We Th Fr Sa
             1  2  3
 4  5  6  7  8  9 10
11 12 13 14 15 16 17
18 19 20 21 22 23 24
25 26 27 28 29 30 31
bin  tel
$ ls -l
total 2
drwxrwxr-x   2 aeb       1024 Aug  6 23:51 bin
-rw-rw-r--   1 aeb         37 Aug  6 23:52 tel
$ cat tel
maja    0501-1136285
peter   0136-7399214
$ cp tel tel2
$ ls -l
total 3
drwxr-xr-x   2 aeb       1024 Aug  6 23:51 bin
-rw-r--r--   1 aeb         37 Aug  6 23:52 tel
-rw-r--r--   1 aeb         37 Aug  6 23:53 tel2
$ mv tel tel1
$ ls -l
total 3
drwxr-xr-x   2 aeb       1024 Aug  6 23:51 bin
-rw-r--r--   1 aeb         37 Aug  6 23:52 tel1
-rw-r--r--   1 aeb         37 Aug  6 23:53 tel2
$ diff tel1 tel2
$ rm tel1
$ grep maja tel2
maja    0501-1136285
$
```
여기서 컨트롤+D를 입력시킴으로써 세션을 종료시켰습니다.

**$**는 명령 프롬프트입니다.--이것은 쉘이 다음 명령을 받아드릴 준비가 되었다는 표시입니다.
## 경로명과 현재 디렉토리

## 디렉토리

## 디스크와 파일시스템

## 프로세스

## 정보 얻기
수천 개의 명령어들과 뒤따르는 수 많은 옵션들이 있습니다.

# 같이 보기 
ash(1), bash(1), chsh(1), csh(1), dash(1), ksh(1), locate(1), login(1), man(1), xterm(1), zsh(1), wait(2), stdout(3), man-pages(7), standards(7)

# 원본
본 페이지는 리눅스 man-페이지 프로젝트의 5.13버전의 일부입니다. 이 프로젝트의 설명, 정보, 버그 제보 그리고 이 페이지의 최신 버전의 https://www.kernel.org/doc/man-pages/ 에서 확인하실 수 있습니다.

