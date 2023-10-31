---
layout: single
title:  "[SWEA] 4371. 항구에 들어오는 배"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWMedCxalW8DFAXd&categoryId=AWMedCxalW8DFAXd&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=8>


  
  
# 과정
1. 주기가 있는 배들의 날짜를 넣기 위한 ans 리스트를 만들어준다.
2. 배의 수를 세기 위한 cnt를 0으로 초기화 해준다.
3. 만약 a[i]가 ans에 있으면 주기가 이미 있는 배 이므로 continue해준다.
4. x에는 새로운 배의 주기를 넣어준다.
5. x주기의 배에 해당하는 일수를 ans에 넣어준다.
6. 테스트 케이스 번호와 cnt를 출력해준다.





# 정답 코드
<script src="https://gist.github.com/kghees/cb4de8c5ce4dea0eccc779ae8726a29a.js"></script>