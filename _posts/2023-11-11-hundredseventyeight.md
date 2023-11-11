---
layout: single
title:  "[SWEA] 5432. 쇠막대기 자르기"
categories: SWEA
tag: [python, D4]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=4&contestProbId=AWVl47b6DGMDFAXm&categoryId=AWVl47b6DGMDFAXm&categoryType=CODE&problemTitle=&orderBy=INQUERY_COUNT&selectCodeLang=PYTHON&select-1=4&pageSize=10&pageIndex=3>




  
  
# 과정

1. 쇠막대기들을 저장할 stack 리스트를 만들고 
잘려진 쇠막대기들의 수를 저장할 res를 0으로 정의해준다.
2. 만약 s[i]가 '(' 이라면 stack에 추가해준다.
3. s[i]가 ')'인데 바로 전 쇠막대기가 '('이라면 레이저 이므로 stack에서 마지막 '('를 pop해주고 잘려진 쇠막대기 수는 현재 stack에 있는 쇠막대기들의 수와 같으니 res에 더해준다.
4. s[i]가 ')'인데 바로 전 쇠막대기가 ')'이라면 쇠막대기 하나의 끝부분 이므로 stack에서 pop해주고 res에 1을(레이저에 의해 하나의 막대기가 잘린 부분의 끝부분) 더해준다.
5. 테스트 케이스 번호와 잘린 쇠막대기의 수를 출력한다.



# 정답 코드
<script src="https://gist.github.com/kghees/4b4a495b3d3c5b05609b36641d699180.js"></script>
  



