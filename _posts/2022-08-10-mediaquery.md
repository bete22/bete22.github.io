---
layout: single
title: "[CSS] 미디어쿼리"
categories: CSS
tag: [CSS, mediaquery]
toc: true 
toc_sticky: true
author_profile: false
---



# 미디어쿼리, 뭐할 때 써? 



화면의 크기가 바뀜에 따라  웹 페이지의 각 요소들도 **바뀐 화면에 최적화된 디자인으로 보여주기 위해** 사용. 





# 어떻게 쓰면 돼? 



1. **화면 크기 파악** (개발자도구)

2. **미디어쿼리 선언** 

   - 기본 문법 

   ```
    @media(화면크기 조건){ 선택자{속성:값;} } 
   ```

   - 예시 

   ```css
    @media(min-width:800px){
   
      		div{display:none;}}
   
   ```

   화면 크기가 800px이 넘어가면 display:none;이 되게끔 하라는 뜻 





 

