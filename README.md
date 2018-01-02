# Latte-Dash

> Latte-Dash project

## Goal

```bash
  Study for vue...
```


## 프로젝트 구조 설명

참고 : [guide] ( http://itstory.tk/entry/vuecli-Webpack-%ED%85%9C%ED%94%8C%EB%A6%BF%EC%9C%BC%EB%A1%9C-vuejs-%EA%B0%9C%EB%B0%9C%ED%99%98%EA%B2%BD-%EA%B5%AC%EC%B6%95%ED%95%98%EA%B8%B0 )

```bash
- build
  배포시 관련 설정들이 들어있는 폴더
- config
  webpack 관련 설정들이 포함 되어있는 폴더
- package.json
  npm 의존성 모듈 목록들과 개발/테스트/배포 할 수 있는 명령어들이 포함되어있음
- src
  vuejs 로 개발을 진행 할 수 있으며 vue-router가 미리 설정 되어 있음
- static
  vuejs 와 관련없이 공통으로 사용해야 할 정적 파일들을 이곳에서 보관하도록 한다
- test
  개발 하면서 유닛테스트를 진행 할 수 있도록 준비되어 있는 test 폴더
- dist
  빌드를 완료하면 dist 폴더에 모든 파일과 index.html 까지 포함 되어 있다.
  이 폴더 안에 있는 모든 파일을 배포 공간에 넣어두면 서비스를 운영 할 수 있다

```



## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
