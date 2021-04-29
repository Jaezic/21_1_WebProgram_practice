## 2021학년 1학기 WebProgram 연습 1

---

- 기술참조: 가천대학교 소프트웨어전공 강의(웹프로그래밍)
- 개발언어: Html
- 개발환경: macOS Big Sur, MacBook Air(M1, 2020)
- 실행환경: Safari for mac

---

### 20210315 학습내역(아래)
#### 21_1_exercise1.html
- META Element 이용
- HEAD 태그 속 TITLE 태그를 이용해 웹 제목 생성
- ALIGN Attribute를 이용해 정렬 방법

#### 21_1_exercise2.html
- Heading Tag Level을 이용해 텍스트 크기 조절
- Paragraph Tag(p), Comments Tag(!-- --), LineBreak Tag(br), Horizontal Rule Tag(hr), List Tag(ul,li,ol,dl,dt,dd) 이용
- List Tag를 이용해 Nested List 꾸리기

#### 21_1_exercise3.html
- body 태그에 color Attributes를 이용해 배경색 변경

#### 21_1_exercise4.html
- Table(table), Rows(tr), Data in a row(td), Header(th), Caption(caption)
- Border Attribute를 이용해 테두리 크기 조정
- Cell Padding & Spacing Attributes를 이용해 표 안 여백, 셀 사이의 거리 조정
- Cell Merge Attriubtes의 rowspan, colspan을 이용해 표 병합

### 20210316 학습내역(아래)
#### 21_1_exercise5.html
- Hyperlink Tag의 Link to Another Document에서 Absolute link로 이동하기
- Hyperlink Tag의 Target Attribute의 _blank로 새 창으로 이동하기
- Anchor Tag의 name Attribute 그리고 href Attribute을 통해 Specific Section으로 이동하기

#### 21_1_exercise3.1.html
- blockquote tag를 이용해 인용구 만들기
- image tag(tag)에서 Relative link를 사용해 이미지 불러오기

### 20210318 학습내역(아래)
#### 21_1_exercise3.2.html
- input tag로 type attribute를 이용해 checkbox, radio, text, password 이용하기
- radio 형은 반드시 name attribute가 같아야 한다
- select tag와 option tag로 선택 창 만들기
- select tag에 size attriubute를 이용해 열거형 리스트 생성
- form tag에 method attribute를 이용해 정보를 전달할 수 있다. (GET, POST)
- textarea tag로 rows와 cols attribute를 설정해 다중 라인 텍스트를 표시할 수 있다.
- input tag로 type attribute에서 button, submit, reset을 이용할 수 있다.

### 20210323 학습내역(아래)
#### 21_1_exercise4.1.html
- Internal 형으로 CSS(Cascading Style Sheet) 이용하기 <style type="text/css">
- selector를 지정해 property 이용하기 (background-color, color)
- Inline 형으로 CSS 이용하기 (tag 안 style attribute)

### 20210325 학습내역(아래)
#### 21_1_exercise4.2.html
- External 형으로 CSS 이용하기 <link rel="stylesheet" type="text/css" href=""> or @import url(""); or @import "";
- ID selector로 style 지정하기 (#)
- Class slector로 style 지정하기 (.)
- ID는 unique(only one ID, only one element), Class는 NOT unique(multiple elements, multiple classes)

### 20210330 학습내역(아래)
#### 21_1_exercise5.1.html
- div tag 통해 block 형으로 영역 나누기
- span tag 통해 inline 형으로 영역 나누기
- font-style,weight,size,family,variant property 이용하기
- border-style,color|padding|margin property 이용하기
- tag의 nested 관계에 따라 selector의 property는 상속될 수 있다.
- font-size 와 font-family property가 같이 필요하다.
- text-align,decoration,transform 으로 글씨 포맷 설정할 수 있다.
- width, height property를 이용해 크기 설정하기
- width, height property에 값을 auto, length(px,cm,etc), %로 입력한다.
- background-color,image,position,size,repeat,origin,attachment를 통해 영역의 뒷배경을 설정할 수 있다.

### 20210401 학습내역(아래)
#### 21_1_exercise5.2.html
- float property를 이용해 영역 나누기
- display property를 이용해 inline, block, none 설정하기

### 20210406 학습내역(아래)
#### 21_1_exercise5.3.html
- verticial-align property를 이용해 수직 정렬하기
- text-decoration-line property를 이용해 하이퍼링크 밑줄 지우기
- @media CSS media의 print 타입을 이용해보기
- anchor의 Pseudo-class 이용하기(:link, :visited. :hover)
- first-child Pseudo-class 이용하기 ex) p:first-child, p i:first-child, p:first-child i
- style 적용의 순은 weight(!important) -> specificity(element<class<id) -> order(last line)이다.
