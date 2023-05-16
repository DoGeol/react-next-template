# package.json
```shell
# 1. 기본 설정 수정
npm i --D @types/node @types/react @types/react-dom eslint eslint-config-next typescript

# 2. airbnb + 종속 패키지까지 설치하기
npx install-peerdeps --dev eslint-config-airbnb
npm i --D eslint-config-airbnb-typescript @typescript-eslint/eslint-plugin @typescript-eslint/parser

# 3. prettier
npm i --D prettier eslint-plugin-prettier eslint-config-prettier

 
```