---
layout: single
title:  "[BOJ/백준] 28278. 스택 2"
categories: CodingTest
tag: [stack, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/28278>



  
  
# 과정

1. 명령을 실행할 stack 리스트를 만들어준다.
2. a[0]이 1이라면 stack에 a[1]을 추가한다.
3. a[0]이 2라면 stack이 비어있지 않으면 스택에 있는 마지막 수를 출력하고 pop해준다.  
비어있으면 -1을 출력한다.
4. a[0]이 3이라면 stack의 길이를 출력해준다.
5. a[0]이 4라면 stack이 비어있으면 1을 출력 그렇지 않으면 0을 출력해준다.
6. a[0]이 5라면 stack이 비어있지 않으면 stack의 마지막 수를 출력하고 비어있으면 -1을 출력해준다.


# 정답 코드

<script src="https://gist.github.com/kghees/f77130fd83b3c80a69ab3c6d7acac00b.js"></script>
    




