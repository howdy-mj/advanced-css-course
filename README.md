# Advanced CSS Course

Udemy - Advanced CSS and Sass: Flexbox, Grid, Animations and More!
[Github](https://github.com/jonasschmedtmann/advanced-css-course)

### sass to css

```
$ npm run watch:sass
```

`-w`는 watch의 줄임말로 수정사항을 계속 보고 있음

### css 최적화

자세한 내용은 `1-Natours/package.json` 참고

```
# CSS 파일들을 하나로 합쳐주는 패키지
$ npm install --save-dev concat

# 여러 브라우저에서 지원되도록 도와주는 패키지
$ npm install autoprefixer postcss-cli --save-dev
```

명령어

```
# scss를 css로 변환
$ npm run compile:sass

# css 파일을 합침
$ npm run concat:css

# webkit 넣어줌
$ npm run prefix:css

# 압축
$ npm run compress:css
```

위의 네가지를 한 번에 실행시켜주는 패키지 설치 및 명령어

```
$ npm i npm-run-all --save-dev
$ npm run build:css
```
