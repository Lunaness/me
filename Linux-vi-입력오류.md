 http://ledgku.tistory.com/23
 
 VIM 설치 방법

- 터미널을 띄운다.(Ctrl + Alt + T)
- $ sudo apt-get update 엔터
- $ sudo apt-get install vim 엔터
- vim ~/.vimrc (vim 설정 파일. 하이라이팅, 인덱스, 공백 칸 수등 설정을 할 수 있다.)
- 아래 설정 내용을 입력하고 저장한다.


set number            " 줄 번호 표시
set tabstop=4         " tab을 4칸으로
set ignorecase      " 검색시 대소문자 구별하지 않음
set hlsearch         " 검색시 하이라이트
set fileencodings=utf-8,euc-kr    " 파일인코딩 형식
set bs=indent,eol,start    " backspace 키 사용
set ruler              " 상태표시줄 커서 위치 표시
set title               " 제목 표시
set showmatch    " 매칭되는 괄호 표시
set nowrap         " 자동 줄바꿈 해제
set wmnu           " tab 자동완성시 가능한 목록 표시

syntax on        " 문법 하이라이트


출처: http://ledgku.tistory.com/23 [견우와 직녀]
