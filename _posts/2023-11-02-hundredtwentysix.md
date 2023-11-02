---
layout: single
title:  "[SWEA] 18662. 등차수열 만들기"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AYo-e9EKmGoDFAQI&categoryId=AYo-e9EKmGoDFAQI&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=11>


  
  
# 과정
1. 등차수열이 b-a = c-b 이므로 2b = a+c가 된다.  
그러므로 res에 abs(b-(a+b)/2) 한 값을 넣어준다.
2. 테스트 케이스 번호와 소수점 아래 첫째 자리 까지 res를 출력한다.


 




# 정답 코드
<script src="https://gist.github.com/kghees/3776eb4ca0ce7b4f8c962bcfef2a2f77.js"></script>