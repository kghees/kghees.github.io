---
layout: single
title:  "[BOJ/백준] 13241. 최소공배수"
categories: CodingTest
tag: [유클리드 호제법, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/13241>



  
  
# 과정

1. x,y에 각각 a,b를 넣어준다.
2. y가 0이 아닐때 까지 x % y해서 x에 넣어주고 x,y를 바꾸어준다.
3. a,b를 곱한것에서 x(최대공약수)를 나눈 몫이 최소공배수이므로 출력해준다.



# 정답 코드

<script src="https://gist.github.com/kghees/cb23d73ddd9710bc311f7dd07a4424fa.js"></script>
  
    




