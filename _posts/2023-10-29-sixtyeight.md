---
layout: single
title:  "[SWEA] 3499. 퍼펙트 셔플"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWGsRbk6AQIDFAVW&categoryId=AWGsRbk6AQIDFAVW&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=5>

  
  
# 과정
1. 결과 값을 저장할 res를 빈 리스트로 저장
2. a의 길이가 짝수일 때  
arr은 a의 절반까지의 리스트를 저장하고  
brr은 나머지 절반의 리스트를 저장한다.  
res에 arr먼저 pop(0)하고 brr도 pop(0) 해서 저장
3. a의 길이가 홀수일 때  
arr은 a의 절반에 +1까지의 리스트를 저장하고  
brr은 나머지 리스트를 저장한다.  
res에 arr먼저 pop(0)하고 brr도 pop(0) 해서 저장  
홀수 이므로 arr에 1개의 카드가 남으므로 남았다면 res에 저장
4. 테스트케이스 번호와 res를 출력






# 정답 코드
<script src="https://gist.github.com/kghees/7d65c921c1ff6c84d8e61945387f9bee.js"></script>