
#갤럭시 dex를 이용한 개발환경 구축 정리

#마켓에서 Termux 설치

#Termux를 통해 unbuntu 설치
```
* Apt (Advanced Package Tool 의 약어) 는 Debian 시스템에 포함된 핵심 도구들의 집합체

-apt update 입력 (apt 명령어가 없으면 pkg install apt 로 설치)
-apt upgrade 입력

* proot-distro : 리눅스 배포판을 설치 하기 위한 패키지 관리

-apt install proot 입력 
-apt install proot-distro 입력
-proot-distro list 입력하여 리눅스 목록을 확인해본다
-proot-distro install ubuntu 입력하여 우분투 설치 

-우분투 설치가 완료되면
proot-distro login ubuntu 입력하여 우분투에 로그인한다 

* 우분투에 로그인 성공시 우분투 리눅스 환경임으로 apt를 업데이트 해줘야함.
-apt update 입력 
-apt upgrade 입력

-vim 설치를 위해
apt install vim 입력 

참조 : https://m.blog.naver.com/wonjinho81/222597996987
```
