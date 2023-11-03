---
layout: single
title:  "[SWEA] 12741. 두 전구"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AXuUo_Tqs9kDFARa&categoryId=AXuUo_Tqs9kDFARa&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=12>


  
  
# 과정
1. 문제의 테스트 케이스가 5만개 이므로 결과 값을 모았다가 한번에 출력할 res 리스트를 만들어준다. 
2. 켜진 전구마다 1을 더해주기 위해 num 리스트를 만들어준다.
3. a~b초 사이에 켜진 전구에 1을 더해주고  
c~d초 사이에 켜진 전구에도 1을 더해준다.
4. num 리스트에서 2인 값을 res에 추가해준다.
5. 테스트 케이스 번호와 res리스트 값을 순서대로 출력해준다.


 




# 정답 코드
<script src="https://gist.github.com/kghees/8632dc811b3a7696631c73af951c8b27.js"></script>