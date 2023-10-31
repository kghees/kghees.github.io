---
layout: single
title:  "[SWEA] 5215. 햄버거 다이어트"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWT-lPB6dHUDFAVT&categoryId=AWT-lPB6dHUDFAVT&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=9>


  
  
# 과정
1. 햄버거 조합을 저장할 d 리스트를 만들어준다.
2. 입력받은 score(점수)는 a[i][0]이고 cal(칼로리)는 a[i][1]이다.
3. 만약 cal이 j보다 크다면 칼로리를 넘어가는 경우 이므로
d[i][j]는 d[i-1][j](이전점수,같은무게)를 넣어준다.
4. cal이 j보다 작다면 칼로리를 넘어가지 않은 경우 이므로  
d[i][j]는  d[i-1][j](이전점수, 같은무게)와 d[i-1][j-cal]+score(점수를 채운뒤 남은 칼로리를 채울수 있는 최댓값)중 큰 것을 넣어준다.
5. res에 d리스트중 가장 큰 점수값을 넣어준다.
6. 테스트 케이스 번호와 res를 출력해준다.





# 정답 코드
<script src="https://gist.github.com/kghees/be716dcd7121934acdf4ce5dd574e57a.js"></script>