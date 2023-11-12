---
layout: single
title:  "[BOJ/백준] 2885. 초콜릿 식사"
categories: CodingTest
tag: [Greedy, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/2885>



  
  
# 과정

1. 초콜릿 크기가 2의 제곱수 이므로 초콜릿 크기를 찾기위해 i를 1로 정의하고 몇 번 쪼개는지 셀 res를 0으로 정의해준다.
2. k가 2**i보다 작으면 i에 계속 1을 더해준다.
3. x에는 초콜릿의 크기를 넣어준다.
4. k가 x보다 크거나 같으면 k에서 x만큼 빼준다.(k개가 맞는지 세야하므로)
5. 그게 아니라면 x를 2로 나누고 res(쪼갠 횟수)에 1을 더해준다.
6. 초콜릿의 크기와 쪼갠 횟수를 출력해준다.



# 정답 코드

<script src="https://gist.github.com/kghees/2c773aea139095247d41eefca886ca03.js"></script>
  
    




