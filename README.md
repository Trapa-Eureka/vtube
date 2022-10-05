* #1
- [x] git remote add
- [x] npm init

* #2
1. node index.js : 일시적인 실행방법이나 추천하지는 않음.
2. package.json에 scripts추가 (실행하고 싶은거)
3. npm i express
   1. node_modules과 package-lock.json 생성
   2. dependencies에 대한 이해가 필요(플젝에 필요한 묘듈들)
   3. 반대로, npm i express 후 node_module과 package-lock.json을 삭제후 그냥 npm i 만 해도 npm이 자동으로 package.json의 dependencies를 찾아 express 포함 관련 모듈일 알아서 설치해줌. (필요한 정보가 dependencies에 있기 때문)
   4. 만약 프로젝트를 공유하고자 하면 package.json, package-lock.json, index.js만 보내주면 됨.