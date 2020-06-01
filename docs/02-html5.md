# HTML5

> 필수 or 유용 태그들에 대해 배울 예정

## tag 구성요소

```html
<name attribute="value">Content</name>
```

ex.

```html
<a href="http://google.com">Go to google</a>
```

## 문서구조

```html
<!DOCTYPE html>
<!--html5 라고 해석됨을 브라우저에게 알림-->
<html>
  <head>
    <!--information: 보여지진 않지만 문서에 필요한 정보를 담음-->
    <title>This is my title</title>
  </head>
  <body>
    <!--content: 실제 문서가 보여지는 영역-->
    <h1>This is my big title</h1>
    <h6>This is my smallest title</h6>
    Hello World!
  </body>
</html>
```

## meta

> `<header>` 에 적는 추가 정보

```html
<meta charset="utf-8" />
<!--문서(글자) 표현 방식-->
<meta name="author" content="daehun" />
<!--제작자 이름-->
<meta name="description" content="Kokoa Clone" />
<!--검색 시 상세설명으로 보여짐-->
```

## `semantic` vs `non sematic tags`

### semantic tag

> 어떤 의미를 담음, 제목/문단/내비게이션 등등...

- `<section>`
- `<header>`
- `<article>`

### non semantic tag

> 어떤 의미도 없음

- `<div>`: 박스
- `<span>`: 텍스트를 위한 박스

## id & class

> html엔 엄청많은 태그가 있어 많이 헷갈림. 그래서 해당 태그가
> 어떤 의미인지 알아야하는데, ID와 class로 구분 가능

### id

- element(tag) 마다 하나씩 => unique

### class

- 공유되는 속성을 가져야한다면 클래스

sample

```html
<section>
  <header id="header01" class="dafaultHeader">
    <h1>Title of a section</h1>
  </header>
</section>

<div>
  <header id="header02" class="defaultHeader">
    Title of the unkonw container
  </header>
</div>
```
