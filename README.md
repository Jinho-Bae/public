# 시작하기 전
* facebook.com ui를 잘 만들기 위해 만든 library
* component : 사용자 정의 태그
    * 가독성
    * 재사용성
    * 유지보수 편리성
# 개발환경
## toolchain - Create React App
https://github.com/facebook/create-react-app
Win+R > cmd
1. npm install -g create-react-app
2. 설치 후 버전 확인
create-react-app -V
3. react-app dirctory 생성
4. cd 3의 path
5. create-react-app .
3에서 생성한 directory에 개발에 필요한 환경 세팅
6. npm start
Starts the development server.
7. (build 할 때(배포)) npm run build
8. npm install -g serve (npx serve)
install web server
9. serve -s build
build directory를 root로 하겠다

npx : 그때마다 다운로드 받기
항상 최신 버전을 받는 장점은 있지만 1회성임

# without React
public : npm start 했을 때 document root

html 코드가 길어지면 tag를 모듈화할 동기가 생긴다.
이렇게 모듈화(component화) 해주는 게 React