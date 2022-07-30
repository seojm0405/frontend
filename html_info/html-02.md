### meta
​
-   웹페이지의 정보를 정의 할 때 사용
-   head 요소 내부에 위치해야 한다.
​
```
<head>
    <meta charset="UTF-8">
    <meta name="keyword" content="HTML, meta, tag, element, reference">
    <title>HTML meta tag</title>
</head>
```
​
### link
​
-   외부문서를 연결할 때 사용
-   head 요소 내부에 위치해야 한다.  
    **ex**
​
주로 스타일시트를 연결할 때 사용
​
-   `<head> <link rel="stylesheet" type="text/css" href="/examples/media/expand_style.css"> </head>`
​
### style
​
-   문서의 스타일을 설정하는 태그(css를 작성한다)
    
    ````
    <head>
      <style>
          body { background-color: lightpink }
          h1 { color: red; }
          p { text-decoration: underline; }
      </style>
    </head>
    ```'
    ````
    
​
### script
​
-   javascript를 불러오거나 작성하기 위한 영역
​
### title
​
-   문서의 제목을 표시
-   제목 표시줄이나 브라우저 탭이름으로 표시됨
​
### head
​
-   웹 브라우저가 해석해야 할 html 문서의 정보
-   제목, 문자 인코딩 방식, 외부 파일 위치 등
​
```
<!DOCTYPE html>
<html lang="ko">
<head>
    <title>HTML 문서의 제목입니다.</title>
</head>
<body>
    HTML 문서의 콘텐츠(contents) 영역입니다.
</body>
</html>
```
​
### body
​
-   웹 브라우저가 해석해야 할 html 문서의 구조
-   일반적으로 사용자에게 보여지는 부분에 해당
