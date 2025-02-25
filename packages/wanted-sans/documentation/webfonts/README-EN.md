[한국어](./README.md) | [**English**](./README-EN.md)

# Webfonts

You can use Wanted Sans via jsDelivr, a widely-used public CDN.

## font-family

For a consistent experience across platforms, the following font-family are recommended:

```css
font-family: "Wanted Sans Variable", "Wanted Sans", -apple-system, BlinkMacSystemFont, system-ui, "Segoe UI", "Apple SD Gothic Neo", "Noto Sans KR", "Malgun Gothic", "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", sans-serif;
```

## Variable Dynamic Subset

To swiftly and efficiently use Wanted Sans with varying weights while only downloading characters present on the page, use the code below. The font-family to use is "Wanted Sans Variable".

#### HTML

```html
<link rel="preconnect" href="https://cdn.jsdelivr.net" crossorigin="anonymous" />
<link rel="preload" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans/fonts/webfonts/variable/split/WantedSansVariable.min.css" />
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans/fonts/webfonts/variable/split/WantedSansVariable.min.css" />
```

#### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans/fonts/webfonts/variable/split/WantedSansVariable.min.css");
```

## Standard Dynamic Subset

For compatibility with older browsers while maintaining a fast and smooth experience with Wanted Sans, use the code below. The font-family to use is "Wanted Sans".

#### HTML

```html
<link rel="preconnect" href="https://cdn.jsdelivr.net" crossorigin="anonymous" />
<link rel="preolad" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans/fonts/webfonts/static/split/WantedSans.min.css" />
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans/fonts/webfonts/static/split/WantedSans.min.css" />
```

#### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans/fonts/webfonts/static/split/WantedSans.min.css");
```

## Standard Webfonts

To use Wanted Sans with all its features, use the code below. The font-family to use is "Wanted Sans".

#### HTML

```html
<link rel="preconnect" href="https://cdn.jsdelivr.net" crossorigin="anonymous" />
<link rel="preload" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans/fonts/webfonts/static/complete/WantedSans.min.css" />
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans/fonts/webfonts/static/complete/WantedSans.min.css" />
```

#### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans/fonts/webfonts/static/complete/WantedSans.min.css");
```

## Variable Webfonts

To use Wanted Sans with all its features, including variable weight properties, use the code below. The font-family to use is "Wanted Sans Variable".

#### HTML

```html
<link rel="preconnect" href="https://cdn.jsdelivr.net" crossorigin="anonymous" />
<link rel="preload" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans/fonts/webfonts/variable/complete/WantedSansVariable.min.css" />
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans/fonts/webfonts/variable/complete/WantedSansVariable.min.css" />
```

#### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/wanteddev/wanted-sans@v1.0.1/packages/wanted-sans/fonts/webfonts/variable/complete/WantedSansVariable.min.css");
```
