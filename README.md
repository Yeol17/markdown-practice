# 마크다운

## 장점
- 문법이 쉽고 간결하다.
- 관리가 쉽다.
- 지원 가능한 플랫폼과 프로그램이 다양하다.

## 단점 
- 표준이 없다.
- 모든 html 마크업을 대신하지 못한다.

# 제목(Header)

# 제목 1 
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br/>
대한 사함 대한으로 길이 보전하세 

( 띄어쓰기 2번 or &lt;br/&gt; )

# 강조(Emphasis)

_이탤릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>  

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)

<a href="https://google.com">GOOGLE</a>  

[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동" target="_blank">NAVER</a>

[NAVER](https://naver.com "NAVER로 이동")

# 이미지(Images)

![]()

![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
>(네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중첩된 인용문1  
>>> 중첩된 인용문2  
>>> 중첩된 인용문3 
>>>>중첩돤 인용문

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소애 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a href="https://www.googole.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA'
  return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

# 표(Table)

position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)

동해물과 <span style="text-decoration:underline;">백두산</span>이 마르고 닳도록 <br/>
하느님이 보우하사 우리나라 만세

<a href="https://naver.com" title="NAVER로 이동" target="_blank">NAVER</a>

---

<img width="70px" src="https://heropy.blog/css/images/logo.png" alt="HEROPY" />

# 수평선(Horizontal Rule)

---

***

___

<br>

# README 작성 요령

## 1. 프로젝트의 목적 및 용도  
프로젝트에 재해 간단하게 설명하는 내용을 포함하는 것이 좋다.
- 이 프로젝트는 무엇을 위한 것인가
- 어떤 문제를 해결할 수 있는가
- 왜 이 프로젝트가 유용한가
-  어떤 사람들이 이 프로젝트를 사용하면 좋은가
- 이 프로젝트는 어떻게 작동하는가

## 2. 프로젝트를 시작하는 방법
프로젝트를 처음 사용하기 위해 필요한 내용을 포함하는 것이 좋다.
- 프로젝트를 설치, 사용하기 위해 필요한 전제조건인 있는가
- 어떻게 설치, 사용, 테스트 하는가
- 설치 가이드 문서는 어디에 있는가

## 3. 저작권, 라이선스 정보
프로젝트의 사용 범위 및 조건을 설명하는 내용을 포함하는 것이 좋다.
- 어떤 라이선스로 배포되는가?
- 상세한 라이선스 정보는 어디에서 확인할 수 있는가
- 프로젝트를 사용함에 있어 제약 조건이 있는가(특허, 상업적 사용)

## 4. 외부 리소스 정보
프로젝트 내에 포함도딘 외부의 코드나 리소스의 전보를 포함하는 것이 좋다.
- 각각의 출처 및 배포 라이선스는 무엇인가
<br/>
<br/>

### +참고할 템플릿
[repositoryTemplate](https://github.com/always0ne/repositoryTemplate)

[READEME 템플릿 1](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)

[READEME 템플릿 2](https://github.com/sujinleeme/readme-template/tree/master/korean)