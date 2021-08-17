# CSS_study 

코드는 master에..

## 1. CSS란?

- html 정보를 웹 페이지를 좀 더 아름답게 꾸미는 기능을 함

## 2. 선택자 
1) 태그
2) id : 학번 기능, 하나하나 개별 관리, 어느 딱 한 가지에만 효과를 주고 싶을 때, style 태그에 #
3) class : 반 기능, 그룹핑해 관리하기 쉽게 style 태그에 .
4) 부모 자식
5) 가상 클래스 선택자 : 링크를 꾸며주고, 클래스처럼 동작하기 때문에 가상 클래스 선택자임


## 3. font-size
1) px : 고정
2) em, rem : 가변

사용자에게 권리를 준다는 측면, 정보를 자기 취향대로 볼 수 있게 배려
웹페이지 분석 우클릭: 검사

## 4. color

1) color name
2) rgb
3) hexa

## 5. inheritance

전체를 부모로 다 적용하고 하나만 변경시키는게 효율적

상속이 되는 속성이 있고, 안되는 속성이 있음에 주의

## 6. cascading

하나의 태그에 여러 css가 중첩되면 우선 순위는?

style 속성 > id 선택자 > class 선택자 > li(tag) 선택자 

## 7. inline vs block-level-tag

인라인은 화면 전체를 쓰지 않고 자기 자신 크기만큼 사용

## 8. boxmodel

css에서 가장 많이 사용하는 속성들

padding, margin, width ...

## 9. box-sizing : border-box;

:content-box;

## 10. margin collapse

마진이 겹치면 큰 거로 적용됨

## 11. position 
1) static : 위치와 관련된 설정을 하지 않은 상태(left, right, ..이런거 설정 X)
2) relative : 설정한 상태, 상대적
3) absolute : 절대적
4) fixed : 고정

## 12. flex 

container 와 item

화면이 늘고 줄고 할 때 컨텐츠도 늘고 줄고

겉에 display:flex;

1) flex-direction
2) flex-basis
3) flex-grow : 여백 n빵
4) flex-shrink : 줄어들 때 고통 분담

.item:nth-child(2){} - 아이템 각각을 선택할 수 있게 하는 선택자

## 13. holyGrail layout

성배 레이아웃

header - nav, main, aside(ad) - footer

## 14. multicolumn

신문처럼..열이 여러개

1) column-count
2) column-width
3) column-gap
4) column-rule-style
5) column-rule-width
6) column-rule-color
7) column-span:all -> 컬럼에 구애 받지 않게 자기 위치 그대로


# 알아두면 좋은 것들

## bracket

: <a href="http://brackets.io/">편리한 에디터</a> (나중에 설치해보기)

## 선택자 

다양한 선택자들을 공부하기 위한 <a href="http://flukeout.github.io">웹사이트</a>

## webfont

구글의 <a href="https://fonts.google.com/">웹폰트</a>로 다운, 적용 가능 - 폰트 용량을 고려하자

## Stylish

구글의 <a href="https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe?hl=en-US">Stylish</a> 앱 다운으로 커스터마이징한 것을 공유해 적용 가능
