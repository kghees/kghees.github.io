---
layout: single
title:  "[BOJ/백준] 1747. 소수&팰린드롬"
categories: CodingTest
tag: [수학, 브루트포스, 에라토스테네스의 체, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/1747>



  
  
# 과정

1. 백만 까지의 소수들만 num 리스트에 True로 만들어준다.
2. n ~ 백만까지 i가 1이면 소수가 아니므로 continue해주고  
i가 팰린드롬 수 일 때 i가 소수라면 res에 i를 넣어주고 break해준다.
3. 마지막에 res가 0이라면 res가 백만 일 때 이므로 백 만 일때의
팰린드롬 수 인 1003001을 res에 넣어준다.
4. res를 출력해준다.


# 정답 코드

<script src="https://gist.github.com/kghees/919b6c6c43640775206ab2e9c46ed525.js"></script>




