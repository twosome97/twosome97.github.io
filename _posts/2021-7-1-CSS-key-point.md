---
layout: post
title: css 요점정리
---

# 선택자(style 태그로 같은 종류의 태그들 다 컨트롤 하는것, ex: class, id, 태그 선택자 등)
- 같은 선택자들의 명령이 겹치면 가장 마지막에 내린 명령을 따름
# 상성
- id선택자 > class선택자 > tag선택자 
(id 선택자는 중복 불가, 구체적인 것이 포괄적인 것보다 우선순위 높음)
- id 선택자 사용법: body에서 원하는 태그 바로 뒤에 id="땡땡" 부여해주고, head의 style 태그 사이에 #아까 부여한 땡땡 { } 

# h1 태그는 style a 태그와는 다르게 화면 전체를 씀--> h1은 block level element(=tag), style a 태그는 inline level element
그렇지만 display 속성으로 block 과 inline 자유롭게 변환가능
연속되면 block은 전체를 쓰니까 줄 바꿈 자동으로 되고, inline은 같은 줄에 써짐 
# box model - 크기 특성 조절 가능
https://www.washington.edu/accesscomputing/webd2/student/unit3/images/boxmodel.gif 구성요소 설명그림
웹페이지 작업 시, 우클릭 후 검사 클릭하면 코딩한 것과 박스 모델이 나옴
그걸로 코딩한 각 부분마다 박스 모델 어느 부분이 다른지 나오는데, 그것을 토대로 고쳐주면 됨

# div , span 태그
div 태그는 블록 엘리먼트이고, 디자인을 위해 구역을 나누는 역할 / span 태그는 인라인 엘리먼트이고 같은 역할임
div 태그가 의미 없으니까 부모태그로 자주 사용됨
