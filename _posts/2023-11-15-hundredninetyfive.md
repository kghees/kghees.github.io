---
layout: single
title:  "[BOJ/백준] 4948. 베르트랑 공준"
categories: CodingTest
tag: [에라토스테네스의 체, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/4948>



  
  
# 과정

1. n의 최대 범위까지 소수들을 num 리스트에 구해준다.
2. n이 0이면 break해준다.
3. 범위안에 소수들을 셀 cnt를 0으로 만들어준다.
4. n+1부터 2n까지 num[i]가 True이면 소수이므로 cnt에 1을 더해준다.
5. cnt를 출력해준다.


# 정답 코드

<script src="https://gist.github.com/kghees/1a3e1536d69ed26414938c17ce46c414.js"></script>
    




