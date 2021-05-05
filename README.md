# 웹표준 핵심가이드북 2 책 실습 
- 소스코드(https://github.com/seulbinim/exHTML5)

## 구현내용 
- `Part3`웹카페 메인페이지(index.html)

## 구현시 고려사항 
- W3C validator error사항 없기 
- openWAX error사항 없기 
- 고정형 페이지 
- 자바스크립트를 이용한 기능구현 없음 (마크업 작업만 진행) 
- IE 지원 고려하지 않음. 
- 벤더프리픽스 고려하지 않음.

### HTML 세부 작업 가이드  
- 이미지는 `assets/img`경로에 존재 
- 폰트는 나눔고딕을 사용하며 `assets/font`경로에 존재 
- 아이콘은 폰트아이콘을 사용하며 `assets/icon`경로에 존재 

### CSS 세부 작업 가이드 
- Normalize 사용. (assets/css/normalize.css)
- color CSS파일 별도 생성 (assets/css/color.css)  
- font CSS파일 별도 생성 (assets/css/font.css)
- icon CSS파일 별도 생성 (assets/css/icon.css)
- layout CSS파일 별도 생성 (assets/css/layout.css)
- 세부 컴포넌트 CSS파일 별도 생성 (assets/css/index.css)

### 스타일 가이드 
#### 폰트 
- 기본 16px (1em)
- 큰글자 20px (1.25rem) 
- 작은글자 12px (0.75rem) 

### 주요사용색깔 
- gray : #cccccc 
  
- white : #ffffff
- white-darken : #f4f4f4
- black : #000000 
- main background linear-gradient

`/* Permalink - use to edit and share this gradient: https://colorzilla.com/gradient-editor/#cccccc+0,ffffff+100 */
  background: #cccccc; /* Old browsers */
  background: -moz-linear-gradient(top,  #cccccc 0%, #ffffff 100%); /* FF3.6-15 */
  background: -webkit-linear-gradient(top,  #cccccc 0%,#ffffff 100%); /* Chrome10-25,Safari5.1-6 */
  background: linear-gradient(to bottom,  #cccccc 0%,#ffffff 100%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#cccccc', endColorstr='#ffffff',GradientType=0 ); /* IE6-9 */
  `
### 아이콘 
- fontello로 사용 (http://fontello.com/)
    - b : 동그라미 
    - c : 체크
    - d : 문서
    - h : 사람
    - p : 더하기
    - r : 네모
    - s : 별표
    - t : 트위터
    - z : 돋보기
    - g : 오른꺽쇄