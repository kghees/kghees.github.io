---
layout: single
title:  "[SWEA] 13038. 교환학생"
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
1. 최소 값을 저장해야 하므로 res를 1e9로 초기화해준다.
2. 7개의 요일에서 a[i]가 1이라면 index에 i값을 넣어주고
x에는 n값을 넣어준다.  
그리고 몇일이 지났는지 셀 cnt를 0으로 초기화해준다.
3. x가 0보다 클때 a[index]가 1이라면 x에서 1을 빼주고
cnt에는 계속 1을 더해준다.  
index값은 하루하루 늘어가야하니 1을 더해주고 7과 나머지 연산을 해준다.  
res가 cnt보다 크면 res에 cnt를 넣어준다.
4. 테스트 케이스 번호와 res를 출력해준다.  
 
  
    
    
# 정답 코드
<script src="https://gist.github.com/kghees/23da19719d8393b48f202b9d9dabda4c.js"></script>