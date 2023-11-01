---
layout: single
title:  "[SWEA] 5986. 새샘이와 세 소수"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWaJ3q8qV-4DFAUQ&categoryId=AWaJ3q8qV-4DFAUQ&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=9>


  
  
# 과정
1. n의 최대 범위까지 소수를 판단해서 ans에 소수들을 넣어준다.
2. 경우의 수를 셀 cnt를 0으로 초기화해준다.
3. i는 ans리스트 길이에서 ans[i]가 n보다 작을때 j범위가 i부터 ans길이까지 ans[j]가 n보다 작을때 k범위가 j부터 ans길이까지에서  
ans[i]+ans[j]+ans[k]가 n과 같다면 cnt에 1을 더해준다.
4. 테스트 케이스 번호와 cnt를 출력해준다.


  




# 정답 코드
<script src="https://gist.github.com/kghees/c2a19734c107bb00a12e77d266350f99.js"></script>
      