---
layout: single
title:  "[SWEA] 10580. 전봇대"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AXO8QBw6Qu4DFAXS&categoryId=AXO8QBw6Qu4DFAXS&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=8>


  
  
# 과정
1. 전봇대에 처음 전선을 넣을 res 리스트를 만들어준다.
2. 교차점을 셀 cnt를 0으로 초기화해준다.
3. res가 빈 리스트가 아니고 a,b중 하나라도 x,y보다 크면 무조건 교차점이 생기니 cnt에 1을 더해준다.
4. res가 빈 리스트이면 a,b를 추가해준다.
5. 테스트 케이스 번호와 cnt를 출력시켜준다.





# 정답 코드
<script src="https://gist.github.com/kghees/f27c40dd462f3cb131d030fcd807a3c2.js"></script>