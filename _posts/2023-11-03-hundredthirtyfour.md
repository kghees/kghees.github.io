---
layout: single
title:  "[SWEA] 6190. 정곤이의 단조 증가하는 수"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AXxNn6GaPW4DFASZ&categoryId=AXxNn6GaPW4DFASZ&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=12>
  
  
# 과정
1. 단조 증가하는 수를 저장할 res 리스트를 만들어준다.
2. a리스트에서 모든 a[i]*a[j]를 check 함수로 검사한다.  
check함수가 True라면 단조 증가하는 수 이므로 res에 추가해준다.
3. check함수에서 x를 문자화 한 후 x[i],x[j]를 정수화 해 x[i]가 크다면 단조 증가하는 수가 될 수 없으므로 False를 return해준다.  
반복문을 무사히 완료했으면 단조 증가하는 수 이므로 True를 return
4. res에 숫자가 들어있으면 테스트 케이스 번호와 res에서 
가장 큰 수를 출력해준다.  
res가 빈 리스트라면 테스트 케이스 번호와 -1를 출력해준다.  
 
  
    
    
# 정답 코드
<script src="https://gist.github.com/kghees/e6f7a1b2d8b94a4c227a68b8bc416a62.js"></script>