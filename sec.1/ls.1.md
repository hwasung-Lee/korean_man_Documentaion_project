# 이름
ls - 디렉토리내 콘텐츠 목록을 출력합니다.

# 사용법
ls [옵션] ... [파일] ...

# 설명
파일들의 정보를 표시합니다.  
(기본적으로는 현재 디렉토리 내에 있는 파일에 대한 정보를 표시합니다.)  
-cftuvSUX 또는 --sort가 특정되어 있지 않을경우,  알파벳 순서대로 정렬합니다.  
긴 옵션들은 짧은 옵션들로 축약이 가능합니다.  

## -a, -all
.으로 시작하는 항목을 무시하지 않고 출력합니다.  
[역자 주] 숨김 파일 또는 디렉토리는 이름이 .으로 시작합니다.

## -A, -almost-all
.과 ..을 표시하지 않습니다.  
[역자 주] 여기서 .은 현재 디렉토리 ..은 이전 디렉토리를 의미합니다.

## --author
-l과 함께 각 파일을 수정한 유저(원문 : the author)을 표시합니다.

## -b, --escape
화면에 표시가 되지않는 문자들에 대해 C스타일 이스케이프 문자로 출력합니다.  
[역자 주] 여기서 C는 프로그래밍 언어중 하나인 C언어를 의미합니다. 

## --block-size=사이즈
-l 옵션과 함께, 목록을 출력할때 옵션으로 지정한 사이즈로 크기를 조절하여 출력합니다.

## -B, --ignore-backups
암시적으로 파일명이 '~'로 시작하는 파일을 출력하지 않습니다
 
## -c

## -C

## --color=[WHEN]
출력결과에 색을 입힘니다.이때 가능한 WHEN옵션은 'always'(항상, 기본적으로 옵션을 생략하였을때도 사용되는 옵션), 'auto'(자동) 혹은 'never'(색을 입히지 않음)입니다.

## -d, --directory


## -D, --dired

## -f

## -F, --classify

## --file-type

## --format=WORD

## --full-time

## -g

## --group-directories-first

## -G

## -h, --human-readable

## --si

## -H, --dereference-command-line

## --dereference-command-line-symlink-to-dir

## --hide=PATTERN

## --hyperlink[=WHEN]

## --indicator-style=WORD

## -i, --inode

## -I, --ignore=패턴
쉘 패턴에 해당하는 항목을 출력하지 않습니다.
## -k, --kibibytes 

## -l 
긴 리스트 포맷을 사용합니다.  
[역자 주] 여기서 '긴 리스트 포맷'은 디렉토리 여부, 권한, 소유자, 소유 그룹, 파일 크기 등을 표시하는 것을 의미합니다.

## -L, --dereference

## -m 

## -n, --numeric-uid-gid

## -N, --literal

## -o

## -p, --indicator-style=slash

## -q, --hide-control-chars

## --show-control-chars

# 저자
Richard M. Stallman과 David Mackenzie 씀

# 버그 제보
GNU Coreutils 온라인 도움말 : <https://www.gnu.org/software/coretuils/>
번역 버그 제보 : <https://www.translationproject.org/team/>

# 저작권
Copyright © 2020 Free Software Foundation, Inc. GPLv3+ 라이센스 : GNU GPL 버전 3 혹은 후기 버전 <https://gnu.org/licenses/gpl.html>.  
본 프로그램은 자유 소프트웨어입니다: 여러분은 자유롭게 수정하고 재배포할 수 있습니다.  
법으로 허용하는 정도에 대한 보증이 없습니다.
# 같이 보기
전체 문서 <https://www.gnu.org/software/coreutils/ls>  
또는 다음을 통해 로컬로 볼 수 있습니다. : info '(coreutils) ls invocation'
