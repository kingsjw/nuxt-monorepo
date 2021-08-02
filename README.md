# monorepo 형태에 nuxt 프로젝트 구성하기

```shell
프로젝트 생성
cd projects && yarn create nuxt-app {프로젝트 이름}

각 서비스에 의존성 설치 # 서비스에서 npm install 하는 것과 동일
lerna bootstrap

각 서비스에서 공통 되는 모듈을 root에 설치
lerna bootstrap --hoist

node_modules 제거
lerna clean

```
