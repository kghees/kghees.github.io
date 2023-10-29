---
layout: single
title:  "[SWEA] 5356. 의석이의 세로로 말해요"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWVWgkP6sQ0DFAUO&categoryId=AWVWgkP6sQ0DFAUO&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=5>

  
  
# 과정
1. 문제 조건에서 나올 수 있는 최대의 경우로 s리스트를 생성한다.
2. s[i][j]에 a[i][j]와 같게 한다.
3. 결과를 넣을 res를 생성한다.
4. 세로로 넣어야하니 s[j][i]가 0이 아니라면 res에 추가해준다.
5. 테스트 케이스 번호와 공백없이 res를 출력해준다.







# 정답 코드
<script src="https://gist.github.com/kghees/3e91e1990274e0284dd75b7b104680ad.js"></script>