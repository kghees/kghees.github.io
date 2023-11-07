---
layout: single
title:  "[BOJ/백준] 16953. A -> B"
categories: CodingTest
tag: [bfs, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/16953>



  
  
# 과정

1. 연산의 횟수를 저장하기위한 res를 -1로 정의해준다.
2. bfs(x,cnt)를 만들어준다 (x:연산되어지는 값, cnt: 연산의 횟수)
3. q를 만들어주고 q에 x,cnt를 추가해준다.
4. 만약 x와 b가 같다면 res에 지금까지의 연산 횟수(cnt)를 저장하고 break해준다.
5. nx가 x*2이거나 x에1을추가한 수 일때 nx가 b보다 작거나 같으면  q에 nx와 cnt+1을 추가해준다.
6. res 값을 출력해준다.





# 정답 코드

<script src="https://gist.github.com/kghees/7fd180c43ebfa3d22b24f0b9d6230780.js"></script>
  
    




