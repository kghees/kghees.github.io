---
layout: single
title:  "[SWEA] 3376. 파도반 수열"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWD3Y27q3QIDFAUZ&categoryId=AWD3Y27q3QIDFAUZ&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=8>


  
  
# 과정
1. 파도반 수열을 적을 d리스트를 만들어준다.
2. d[1],d[2]는 1이므로 1로 초기화해준다.
3. d[i]는 d[i-2]+d[i-3]이므로 3부터 101까지 반복문을 만들어준다.
4. 테스트 케이스 번호와 d[n]을 출력해준다.





# 정답 코드
<script src="https://gist.github.com/kghees/403756ec5c7021c1e81aa8e543ce39eb.js"></script>