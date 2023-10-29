---
layout: single
title:  "[SWEA] 1209. [S/W 문제해결 기본] 2일차 - Sum"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AV13_BWKACUCFAYh&categoryId=AV13_BWKACUCFAYh&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=4>

  
  
# 과정
1. 최대 값을 저장할 res를 0으로 초기화해준다.
2. 행의 합부터 구한다면 x에 0번째 행의 합을 저장하고 x값이 res값 보다 크다면 res에 x값을 저장
3. 열의 합에는 w에 0번째 열의 합을 저장하고 w값이 res값 보다 크다면 res에 w값을 저장
4. y에는 왼쪽 대각선의 합,z에는 오른쪽 대각선의 합을 저장 후
k에는 y,z중 큰 값을 저장하고 k가 res보다 크면 res에 k값 저장
5. 테스트 케이스 번호와 res 값을 출력해준다.






# 정답 코드
<script src="https://gist.github.com/kghees/9054617ee3da241f49c34fcdc8b31213.js"></script>