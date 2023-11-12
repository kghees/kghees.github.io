---
layout: single
title:  "[BOJ/백준] 1459. 걷기"
categories: CodingTest
tag: [Greedy, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/1459>



  
  
# 과정

1. m1에는 평행이동으로만 이동할 때의 값을 넣어준다.
2. m2에는 (x+y)가 2로 나누어지면 모두 대각선 이동한 값을 넣어주고  
아니라면 대각선 이동 + 평행이동1번 한 값을 넣어준다.
3. m3에는 대각선 이동 + 평행이동 한 값을 넣어준다.
4. m1,m2,m3 중 가장 작은 값을 출력해준다.



# 정답 코드

<script src="https://gist.github.com/kghees/a94abc32df48e6b26ae359c1956a6252.js"></script>
  
    




