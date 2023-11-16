---
layout: single
title:  "[SWEA] 1859. 백만 장자 프로젝트"
categories: SWEA
tag: [python, D2]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=2&contestProbId=AV5LrsUaDxcDFAXc&categoryId=AV5LrsUaDxcDFAXc&categoryType=CODE&problemTitle=&orderBy=RECOMMEND_COUNT&selectCodeLang=PYTHON&select-1=2&pageSize=10&pageIndex=1>




  
  
# 과정

1. 판매 이득을 알기 위해 a리스트를 뒤집어서 저장해준다.
2. 판매 이득의 값을 넣을 res와 a리스트의 값들을 넣을 x를 0으로 정의해준다.
3. a리스트에 있는 i에서 x가 i보다 작다면 x에 i를 넣고
res에는 판매 수익(x-i)을 더해준다. 
4. 판매수익이 양수이면 테스트 케이스 번호와 res값을 출력해주고  
음수이면 테스트 케이스 번호와 0을 출력해준다.



# 정답 코드
<script src="https://gist.github.com/kghees/5c80e24196d5f65570679ffe8edaa1c8.js"></script>
  



