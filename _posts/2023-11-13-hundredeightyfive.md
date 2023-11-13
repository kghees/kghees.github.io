---
layout: single
title:  "[BOJ/백준] 11501. 주식"
categories: CodingTest
tag: [Greedy, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/11501>



  
  
# 과정

1. 마지막날 가격부터 최대이익을 비교해보기 위해 a리스트를 뒤집어준다.
2. 가격을 넣을 x와 이익을 계산할 res를 0으로 정의해준다.
3. 만약 i가 x보다 크다면 x에 i를 넣어준다.
4. res에 저장된 x에서 i 값을 빼서 더해준다.
5. res가 0보다 크면 이득이 있는 것이므로 res를 출력해주고  
0보다 작다면 이득이 없는 것이므로 0을 출력해준다.



# 정답 코드

<script src="https://gist.github.com/kghees/b055a8005a01b976f1d4ec827cd70148.js"></script>
  
    




