# css 정리
1. css(cascading style sheet)는 style sheet 라고 얘기함.
2. html의 head안에서 <style></style>로 선언한다.

## CSS 선언
~~~html
<html>
	<head>
		<!-- 각종 링크 및 제목, meta정보를 기재하는 곳 -->
		<style>
			/* 이 영역은 css 영역입니다. */
		</style>
	</head>
	<body>
		<!-- HTML 본문 영역입니다. -->
	</body>
</html>
~~~

## CSS 속성
~~~css
/* 
css의 가장 중요한 개념들 
- display속성: block, inline, inline-block, none
- float()
*/
/* 기본 Block 속성 */
div,  ... Semantic요소
/* 기본 inline 속성 */
a, span, b, img

/* 배경색 */
background-color: red; 

/* 글자와 관련된 속성 */
color: #333;
font-size: 24px; /* 단위: px, %, rem, em, vw, vh ... */
text-decoration: none; /* underline, line-through ... */

/* 글자 정렬과 관련된 속성 */
text-align: center; /* left, right, center, justify */

/* 테두리와 관련된 속성 */
border: 1px solid red;
~~~