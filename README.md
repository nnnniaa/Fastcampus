# 제목(Header)
<!-- <h1>~<h6>태그 -->
# 제목 1
## 제목 2
### 제목 3

 # 문장(Paragraph)

 안녕하세요-!
 반갑습니다.

 # 줄바꿈(Line Breaks)
<!-- <br> or 공백(2개) -->
 안녕하세요-!  
 반갑습니다.

 # 강조(Emphasis)

 _이텔릭_  
 **두껍게**  
 **_이텔릭+두껍게_**  
 ~~취소선~~  
 <u>밑줄</u>

 # 목록(List)
<!-- <ol>태그 -->
 1. 순서가 필요한 목록
 1. 순서가 필요한 목록
 1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
 1. 순서가 필요한 목록

<!-- <ul>태그 -->
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)
<!-- []() -->
<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

[GOOGLE](https://google.com "Google로 이동")

# 이미지(Image)
<!-- ![]() -->
![Uniqlo](https://simage-kr.uniqlo.com/nq/img/logo_2021.svg)
<!-- 그림 클릭 시 링크 이동 -->
[![Uniqlo](https://simage-kr.uniqlo.com/nq/img/logo_2021.svg)](https://google.com)

# 인용문(BlockQuote)

> 인용문  
>> (BlockQuote)

# 인라인(Inline) 코드 강조
<!-- 백틱.. -->
CSS는 ~background~ 속성이 있다.

# 블록(Block) 코드 강조
<!-- 해당 언어의 구문 -->
~~~html
<a href="https://google.com" target="_blank">GOOGLE</a>
~~~

~~~javascript
function func() {
    var a = 'AAA';
    return a;
}
~~~

~~~plaintext
안녕하세요.
~~~

# 표(Table)

position 속성

값 | 의미 | 기본값
--|:--:|--:|
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)

<span style="text-decoration: underline;">안녕</span>하세요,<br>
<u>반갑</u>습니다.

# 수평선(Horizontal Rule)

---

***