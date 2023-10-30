---
layout: single
title:  "[SWEA] 3131. 100만 이하의 모든 소수"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AV_6mRsasV8DFAWS&categoryId=AV_6mRsasV8DFAWS&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=7>


  
  
# 과정
1. 100만이하의 모든 소수 이므로 max를 100만으로 설정해준다.
2. 소수를 판별할 num 리스트를 만들어준다.
3. 범위는 100만의 1/2승 까지 num[i]가 True라면 2의배수부터 3의배수, 4의배수,5의배수 ... False로 만들어주면된다.
4. num 리스트에서 True이면 소수라는 뜻이므로 출력해준다.





# 정답 코드
<script src="https://gist.github.com/kghees/18ba8fc7be7b54b84c20f5d59f1214ea.js"></script>