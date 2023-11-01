---
layout: single
title:  "[SWEA] 11315. 오목 판정"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AXaSUPYqPYMDFASQ&categoryId=AXaSUPYqPYMDFASQ&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=10>


  
  
# 과정
1. 오목이 되는지 판단하기 위한 check를 False로 정의해준다.
2. a리스트에서 a[i][j]가 'o'라면 omok함수의 True, False를 체크해준다.
3. 가로,세로,대각선을 위한 방향벡터 dx,dy를 만들어준다.
4. 돌을 세기위한 cnt를 1로 초기화해준다.
5. 4가지 dx,dy에 대해 돌을 세어준다.
6. 돌의 수가 5이상이면 True를 return해주고 끝날 때까지 5이상이 안된다면 False를 return해준다.
7. check가 True이면 테스트 케이스 번호와 YES를 출력해주고  
check가 False이면 테스트 케이스 번호와 NO를 출력해준다.
  



  




# 정답 코드
<script src="https://gist.github.com/kghees/378b3a07820538b0b2b279551d4c0033.js"></script>
      