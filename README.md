# styling-react 디렉토리는 CH.9의 실습 코드입니다.

# CH.9 컴포넌트 스타일링 , 2021.09.16

## css

- CSS 클래스를 중복되지 않게 만든다. (이름 규칙 혹은 CSS Selector를 활용)

## Sass

- CSS 전처리기로 스타일 코드의 재활용성을 높여주고 가독성을 높임.
- .sass (중괄호와 세미콜론 사용X) 와 .scss(기존 css와 크게 다르지않음) 모두 지원
- 재사용되는 스타일 블록을 함수처럼 사용할 수 있음

## CSSModule

- [파일 이름]_[클래스 이름]_[해시 값] 형태로 자동으로 만들어 컴포넌트 스타일 클래스 이름이 중첩되는 현상을 방지해주는 기술.

## classnames

- CSS 클래스를 조건부로 설정할 때 매우 유용함.

## styled-components

- 자바스크립트 파일 안에 스타일을 선언하는 방식(CSS-in-JS)

## ps. 템플릿 리터럴

₩{javascriptReference} 형태 : 문자열 안에 자바스크립트 레퍼런스 넣기

${} 형태 : (CSS Module의 템플릿 리터럴은) 자바스크립트 객체나 함수를 전달할 때 온전히 추출할 수 있음.
