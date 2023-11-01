---
layout: single
title:  "[SWEA] 6057. 그래프의 삼각형"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWbHcWd6AFcDFAV0&categoryId=AWbHcWd6AFcDFAV0&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=10>


  
  
# 과정
1. 정점들을 저장할 a리스트를 만들어준다.
2. 삼각형 갯수를 셀 cnt를 0으로 정의해준다.
3. 문제 조건이 i < j < k 이므로 순서에 맞게 반복문을 범위를 적어준다.
4. i,j,k가 각각 a[j],a[k],a[i]에 있다면 세 정점이 이어져 있어서 삼각형을 형성 하므로 cnt에 1을 더해준다
5. 테스트 케이스 번호와 cnt를 출력해준다.  
  



  




# 정답 코드
<script src="https://gist.github.com/kghees/4bd18f80246d90ee589876adf023821b.js"></script>
      