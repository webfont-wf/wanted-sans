[**한국어**](./README.md) | [English](./README-EN.md)

# 웹폰트

대표적인 공개 CDN인 jsDelivr를 이용해 Wanted Sans Std를 사용할 수 있습니다.

## font-family

어디서든 동일한 환경을 가지고자 한다면 아래와 같은 font-family 구성을 추천합니다.

```css
font-family: "Wanted Sans Std Variable", "Wanted Sans Std", -apple-system, BlinkMacSystemFont, system-ui, "Segoe UI", Roboto, "Helvetica Neue", "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", sans-serif;
```

## 가변 동적 서브셋

가장 적은 용량으로 가변 굵기와 함께 페이지에 포함된 문자만 선택적으로 다운로드해 보다 빠르고 쾌적하게 Wanted Sans Std를 사용하려면 아래 코드를 사용하세요. 사용하는 font-family 이름은 `"Wanted Sans Std Variable"` 입니다.

#### HTML

```html
<link rel="preconnect" href="https://cdn.jsdelivr.net" crossorigin="anonymous" />
<link rel="preload" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans-std/fonts/webfonts/variable/split/WantedSansStdVariable.min.css" />
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans-std/fonts/webfonts/variable/split/WantedSansStdVariable.min.css" />
```

#### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans-std/fonts/webfonts/variable/split/WantedSansStdVariable.min.css");
```

## 일반 동적 서브셋

오래된 브라우저에도 호환성을 유지하며, 빠르고 쾌적하게 Wanted Sans Std를 사용하려면 아래 코드를 사용하세요. 사용하는 font-family 이름은 `"Wanted Sans Std"` 입니다.

#### HTML

```html
<link rel="preconnect" href="https://cdn.jsdelivr.net" crossorigin="anonymous" />
<link rel="preolad" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans-std/fonts/webfonts/static/split/WantedSansStd.min.css" />
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans-std/fonts/webfonts/static/split/WantedSansStd.min.css" />
```

#### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans-std/fonts/webfonts/static/split/WantedSansStd.min.css");
```

## 일반 웹폰트

모든 기능을 포함한 Wanted Sans Std를 사용하려면 아래 코드를 사용하세요. 사용하는 font-family 이름은 `"Wanted Sans Std"` 입니다.

#### HTML

```html
<link rel="preconnect" href="https://cdn.jsdelivr.net" crossorigin="anonymous" />
<link rel="preload" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans-std/fonts/webfonts/static/complete/WantedSansStd.min.css" />
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans-std/fonts/webfonts/static/complete/WantedSansStd.min.css" />
```

#### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans-std/fonts/webfonts/static/complete/WantedSansStd.min.css");
```

## 가변 웹폰트

가변 weight 속성과 함께 모든 기능을 포함한 Wanted Sans Std를 사용하려면 아래 코드를 사용하세요. 사용하는 font-family 이름은 `"Wanted Sans Std Variable"` 입니다.

#### HTML

```html
<link rel="preconnect" href="https://cdn.jsdelivr.net" crossorigin="anonymous" />
<link rel="preload" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans-std/fonts/webfonts/variable/complete/WantedSansStdVariable.min.css" />
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans-std/fonts/webfonts/variable/complete/WantedSansStdVariable.min.css" />
```

#### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans-std/fonts/webfonts/variable/complete/WantedSansStdVariable.min.css");
```
