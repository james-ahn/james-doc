
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

#unbuntu에서 vscode 설치하기 
```
-apt update && apt install wget -y 입력
-구글에 code server release 를 검색하여 맨 위에 뜨는 깃헙으로 접속
-Assets 링크를 복사 (마우스 우클릭) => code-server-4.1.0-linux-arm64.tar.gz
-termux의 ubuntu 터미널에서 복사된 링크 붙여넣기 
 wget https://github.com/coder/code-server/releases/download/v4.7.0/code-server-4.7.0-linux-arm64.tar.gz
 
-ls 입려시 code-server-4.7.0-linux-arm64.tar.gz 파일이 다운받아져 있음.
-tar 압축을 풀어준다,
 tar -xvf code-server-4.7.0-linux-arm64.tar.gz

- 압축을 푼 폴더로 이동
cd code-server-4.7.0-linux-arm64/bin

-export PASSWORD='원하는 비밀번호' 입력
./code-server 입력
-브라우저를 열어서 주소창에 localhost:8080 입력
-vscode 확인 (비밀번호는 export PASSWORD 입력했던 비번 입력)

참조 :https://idiqpnm.tistory.com/m/7
```

#vscode 환경 세팅
```
- 매번 비밀번호를 입력하기 귀찮음으로 config 파일 수정



```
