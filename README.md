# cra-template-my-first-template

※ 로컬 개발 시스템에 **Node 14.15.5** 이상 버전이 있어야 합니다. <br />
※ 이 템플릿은 **Node 14.15.5** 버전에서 개발 중입니다.

## 시작하기

### 1. 다운로드

```
git clone git clone https://github.com/SMKim94/cra-template-my-first-template
```

### 2. 템플릿 사용

```
npx create-react-app <app-name> --template file:cra-template-my-first-template
cd <app-name>
npm start
```

### 3. 다른 폴더에서 사용

```
cd <path>
npx create-react-app my-app --template file:<path>/cra-template-my-first-template
cd <app-name>
npm start
```

## 기존 Create React App 템플릿과 다른 점이 무엇입니까?

1. SCSS를 기본으로 사용합니다.
2. 한국에서 유명한 고정폭 폰트인 D2Coding 폰트가 내장됩니다.
3. 한국에서 유명한 폰트인 나눔 고딕 폰트가 내장됩니다.
4. Figma 기본 폰트인 Inter 폰트가 내장됩니다.
5. App.js가 화살표 함수 표현식으로 작성됩니다.
6. index.html의 html 언어 속성이 한국어로 설정됩니다.
7. manifest.json에 더 많은 정보가 들어갑니다.
8. BROWSER=none 설정으로 앱 실행시 브라우저를 자동으로 띄우지 않습니다.
9. 빌드시 PUBLIC_URL=. 설정으로 index.html로 실행해도 화면이 나타납니다.

## 다음 목표

1. React Router 적용
2. React Redux와 Redux Toolkit 적용
3. Ant Design 5 적용 및 기본 Layout 구성
4. prettier 적용
