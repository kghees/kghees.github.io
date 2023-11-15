---
layout: single
title:  "[BOJ/백준] 2485. 가로수"
categories: CodingTest
tag: [유클리드 호제법, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/2485>



  
  
# 과정

1. 각 가로수의 차이를 저장할 ans리스트를 만들어준다.
2. 각 가로수들의 차이를 ans 리스트에 넣어준다.
3. t를 ans[0]이라고 하고 ans리스트 숫자들 모두의 최대공약수를 t에 넣어준다.
4. 필요한 가로수의 갯수를 셀 res를 만들어준다.
5. res에 둘 사이에 심을 가로수 개수: 간격 // 최대공약수 - 1 을 더해준다.
6. 가로수의 개수(res)를 출력해준다.



# 정답 코드

<script src="https://gist.github.com/kghees/0974df00b1a9cf4134cfab9f7e0ce5f8.js"></script>
    




