---
layout: single
title:  "[BOJ/백준] 17103. 골드바흐 파티션"
categories: CodingTest
tag: [에라토스테네스의 체, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/17103>



  
  
# 과정

1. n의 범위까지 소수들을 num에 저장해준다.
2. 골드바흐의 파티션의 수를 셀 cnt를 0으로 만들어준다.
3. num[i]와 num[n-i]가 모두 True이면 골드바흐 파티션이 성립하므로
cnt에 1을 더해준다.
4. cnt를 출력해준다.


# 정답 코드

<script src="https://gist.github.com/kghees/eb2a12bca6cc56551378973c2e98ffc6.js"></script>
    




