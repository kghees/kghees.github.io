---
layout: single
title:  "[SWEA] 16002. 합성수 방정식"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AYYAGCNKPgIDFARc&categoryId=AYYAGCNKPgIDFARc&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=9>


  
  
# 과정
1. x,y에 1차이나는 합성수를 곱해준다.
2. 테스트 케이스 번호와 x,y를 출력해준다.  
  
    
      
# 과정2
1. x,y 최대범위까지 반복문을 적어준다.
2. i가 합성수 이어야 하므로 소수가 아닌지 검사할 check함수를 적어준다.
3. i가 check 함수에서 False라면 합성수 이므로  
x-y=n이므로 i-n이 3보다 크고 i-n 또한 합성수인지 판단해준다.
4. 위의 조건을 다 만족하면  
테스트 케이스 번호와 i, i-n을 출력해준다.  





# 정답 코드
<script src="https://gist.github.com/kghees/63a18a59de8cb9fbe3459a549c47ebd8.js"></script>  
  
      
# 정답 코드2
<script src="https://gist.github.com/kghees/975c2ec6808f1a162506f867d3e9fe0b.js"></script>