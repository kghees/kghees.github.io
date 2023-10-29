---
layout: single
title:  "[SWEA] 1206. [S/W 문제해결 기본] 1일차 - View"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AV134DPqAA8CFAYh&categoryId=AV134DPqAA8CFAYh&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=5>

  
  
# 과정
1. 결과 값을 저장할 res를 0으로 저장
2. a[i]의 값보다 양옆 두개의 값들이 작은지를 확인하기위한  
check를 False로 설정
3. a[i] 양옆 두개의 값들에 대해서 a[i]가 크면 check는 True 아니면 check는 False
4. 만약 check가 True라면 a[i] 양 옆 두개의 값들 중 가장 큰 값을 ans에 저장 후  res에 a[i]에서 ans를 뺀 값을 더해준다.
5. 테스트케이스 번호와 res를 출력






# 정답 코드
<script src="https://gist.github.com/kghees/87c1222f1f158cac1775a765b1b8f11e.js"></script>