2.2

index.js 파일을 생성하고
node index.js를 터미널에 입력하여 실행시켰다.

express 설치
npm - node package manager node설치하면 자동으로 설치됌

npm -v 를 입력해서 버전을 봤음

페키지 메니저로 npm을 사용하려면 npm이 정한 방식으로 프로젝트를 시작해야함

npm init을 터미널에 침
정보를 쳐줌
entry point와 test~, git~, keywords~는 생략
author만 자신으로 설정

그러먼 패키지 제이슨이 생기는데 json은 js에서 정보를 담는 방식임

express를 설치하기 시작 함
npm을 실행할때는 제이슨이 있는 곳에서 실행해야함

npm install express

2-3
.gitignore라는 파일을 만들어
node_modules를 깃허브 관리대상에서 제외시킴

https://github.com/github/gitignore/blob/master/Node.gitignore
홈페이지를 통해 node 표준 gitignore를 가져와 복붙했음.
그리고 pakage-lock.json도 보안문제 때문에 제외시킴.

그다음
git remote add origin https://github.com/fennec0987/newtube.git
를 입력시키고
git add .
