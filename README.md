# 116수박화체

[배포처 바로가기](https://blog.naver.com/PostView.nhn?blogId=wosr1&logNo=221324032660&categoryNo=63&parentCategoryNo=46&viewDate=&currentPage=&postListTopCurrentPage=&isAfterWrite=true)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `116 Watermelon`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/116Watermelon/116Watermelon.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/116Watermelon/116Watermelon.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: '116 Watermelon';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/116Watermelon/116Watermelon.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/116Watermelon/116Watermelon.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/116Watermelon/116Watermelon.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/116Watermelon/116Watermelon.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/116Watermelon/subsets/116Watermelon-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/116Watermelon/subsets/116Watermelon-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.



```css
font-family: "116 Watermelon", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
[서체 사용 안내]  

1. 폰트의 지적재산권은 제작자(wosr1@naver.com)에게 있습니다.  

2. 폰트는 개인 및 기업사용자 누구나 무료로 상업사용이 가능하며, 해당 알집파일 형태로 자유롭게 배포가 가능합니다.  

3. 폰트는 어떠한 이유로도 지적재산권 이외의 사용자가 수정, 판매할 수 없으며, 배포되는 형태 그대로 사용해야 합니다.  

4. 해당 폰트를 사용한 2차 제작물은 광고, 홍보 등 활동으로 활용될 수 있습니다.  

5. 해당 폰트 라이선스내용은 변경될 수 있습니다.  

6. 문제발생시 제작자 이메일 또는 쪽지, 블로그 등을 통해 연락주시기바랍니다.  

---------- 
copyright ⓒ 2018 WOO. All rights reserved.  

제작자 - blog.naver.com/wosr1 
이메일 - wosr1@naver.com
```
