# 제목(Header)
<!-- #다음 띄어쓰기로 제목 속성을 가진 글자를 만들 수 있음 -->

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

<br/>
<br/>

# 문장(Paragraph)
동해물과 백두산이 마르고 닳도록 하느님이 보우하사 우리나라 만세 무궁화 삼천리 화려 강산 대한 사람 대한으로 길이 보전하세

<br/>
<br/>


# 줄바꿈(Line Breacks)

#### 1) 줄바꿈 처리 원하는 문장 끝에 띄어쓰기 2번 삽입
<!-- 브라우저에 따라 마크다운이 제대로 출력 되지 않을 수 있음 -->
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산  
대한 사람 대한으로 길이 보전하세  


#### 2) br 태그 삽입
동해물과 백두산이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세<br/>
무궁화 삼천리 화려 강산<br/>
대한 사람 대한으로 길이 보전하세

<br/>
<br/>

# 강조(Emphasis)
_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  <!-- 물결표시(틸드) -->  
<u>밑줄</u>

<br/>
<br/>

# 목록(List)
<!-- 숫자 1.만 넣어주면 자동으로 문장 넘버링 됨 -->
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. (하위) 순서가 필요한 목록
    1. (하위) 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록  
<br/>
<br/>
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

<br/>
<br/>

# 링크(Links)
#### * 기본링크
<!-- html 문법 -->
<a href="https://google.com">GOOGLE</a>  

<!-- 마크다운 문법 -->
[GOOGLE](https://google.com)

<br/>

#### * 마우스 호버 시, title 보여지는 링크
<!-- html 문법 -->
<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>  

<!-- 마크다운 문법 -->
[NAVER](https://naver.com "NAVER로 이동!")

<br/>

#### * 마우스 호버 시, title 보여지는 링크 + 클릭 시 새탭에서 열림
<!-- html 문법 -->
<a href="https://kakao.com" title="KAKAO로 이동!" target="_blank">KAKAO</a>  

<!-- 마크다운 문법 -->
[KAKAO](https://kakao.com "KAKAO로 이동!")

<br/>
<br/>


# 이미지 (Images)

![]()

<!-- []대괄호 안에는 대체텍스트, ()소괄호 안에는 이미지 주소 삽입 -->
![HEROPY](https://heropy.blog/css/images/logo.png)

<!-- 이미지 클릭 시, 이미지에 심어진 링크로 이동 -->
[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)


# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!  
>> 중첩된 인용문  
>>> 중첩된 인용문 1  
>>> 중첩된 인용문 2  
>>> 중첩된 인용문 3 

# 인라인(Inline) 코드 강조

CSS에서 `background` 혹은 `background-image`속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a href="https://google.com" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

<!-- bash = 터미널에서 사용되는 것을 의미 -->
```bash
git commit -m 'Study Markdown'
```

<!-- 순수(단순) 텍스트 입력 -->
```plaintext
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세
```

# 표(Table)

position 속성
<!-- 왼쪽 정렬 -->
값 | 의미 | 기본값  
--|--|--  
static | 기준 없음 | O  
relative | 요소 자신 | X  
absolute | 위치 상 부모 요소 | X  
fixed | 뷰포트 | X  

<!-- 가운데 정렬 -->
값 | 의미 | 기본값  
:--:|:--:|:--:  
static | 기준 없음 | O  
relative | 요소 자신 | X  
absolute | 위치 상 부모 요소 | X  
fixed | 뷰포트 | X  

<!-- 오른쪽 정렬 -->
값 | 의미 | 기본값  
--:|--:|--:  
static | 기준 없음 | O  
relative | 요소 자신 | X  
absolute | 위치 상 부모 요소 | X  
fixed | 뷰포트 | X  


# 원시 HTML(Raw HTML)

동해물과 <span style="text-decoration: underline">백두산</span>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세<br/>

<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a> 

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY" />


# 수평선(Horizontal Rule)

---

***

___


