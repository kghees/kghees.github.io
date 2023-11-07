---
layout: single
title:  "[SWEA] 1218. [S/W 문제해결 기본] 4일차 - 괄호 짝짓기"
categories: SWEA
tag: [python, D4]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=4&contestProbId=AV14eWb6AAkCFAYD&categoryId=AV14eWb6AAkCFAYD&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=4&pageSize=10&pageIndex=2>




  
  
# 과정

1. 괄호를 짝짓기 위한 stack 리스트를 만들어준다.
2. 괄호를 짝지을수 있는지 확인할 check를 True로 정의해준다.
3. 만약 i가 '('라면 stack에 넣어주고 ')'라면 stack이 비어있지 않고 stack의 마지막이 '('라면 짝지을 수 있으니 stack에서 pop해준다.
4. 그것이 아니라면 짝지을 수 없으니 check에 False로 바꾸고
break해준다.
5. 나머지 3개의 괄호에도 똑같이 3번과 4번을 해준다.
6. check가 True이고 stack이 비었으면 모두 알맞게 짝지어졌다는 뜻이므로 테스트 케이스번호와 1을 출력해준다.
7. 그게 아니라면 알맞게 짝지어지지 않았으므로  
테스트 케이스 번호와 0을 출력해준다.






# 정답 코드

<script src="https://gist.github.com/kghees/9470a27f192fdd55c191201841479bdf.js"></script>
  
    




