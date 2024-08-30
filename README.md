# KoPub 돋움체

[배포처 바로가기](https://www.kopus.org/biz-electronic-font2/)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `KoPub Dotum`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/KoPubDotum/KoPubDotum.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/KoPubDotum/KoPubDotum.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'KoPub Dotum';
    font-weight: 300;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/KoPubDotum/KoPubDotum-Light.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KoPubDotum/KoPubDotum-Light.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KoPubDotum/KoPubDotum-Light.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KoPubDotum/KoPubDotum-Light.ttf') format('truetype');
}
@font-face {
    font-family: 'KoPub Dotum';
    font-weight: 500;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/KoPubDotum/KoPubDotum-Medium.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KoPubDotum/KoPubDotum-Medium.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KoPubDotum/KoPubDotum-Medium.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KoPubDotum/KoPubDotum-Medium.ttf') format('truetype');
}
@font-face {
    font-family: 'KoPub Dotum';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/KoPubDotum/KoPubDotum-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KoPubDotum/KoPubDotum-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KoPubDotum/KoPubDotum-Bold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KoPubDotum/KoPubDotum-Bold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/KoPubDotum/subsets/KoPubDotum-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/KoPubDotum/subsets/KoPubDotum-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "KoPub Dotum", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
‘KoPub 서체’ 및 ‘KoPub World 서체’의 지적재산권은 문화체육관광부와 한국출판인회의에 있습니다. ‘KoPub 서체’ 및 ‘KoPub World 서체’의 사용을 허락하고 공개하는 것은 전자책 제작 및 전자출판 유통시장 활성화를 지원하고 출판업계와 전자출판 산업 발전을 도모하기 위함인 동시에, 서체가 공유되고 개선될 수 있는 개방된 환경을 만들기 위함입니다.

‘KoPub 서체’ 및 ‘KoPub World 서체’는 출판업계(전자출판업계 포함) 및 기업, 개인을 포함한 모든 사용자가 별도의 허가절차 없이 홈페이지 정보 등록 후 무료로 사용하실 수 있습니다.

다만, 사전승인 없이 폰트를 수정, 변형하는 것은 불가하며, 폰트 자체를 유료로 판매, 양도하는 모든 상업적 행위는 금지합니다.

‘KoPub 서체’ 및 ‘KoPubWorld 서체’를 사용한 결과물(인쇄물, 광고물(온라인 포함), 전자책 일부의 이미지 등)은
본 서체의 홍보를 위해 활용될 수 있습니다. 이를 원하지 않는 사용자는 언제든지 연락해 주시기 바랍니다.
정확한 사용조건은 서체 라이선스 약관을 참고하시기 바랍니다.
```
