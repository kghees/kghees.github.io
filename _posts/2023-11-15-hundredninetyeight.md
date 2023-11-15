---
layout: single
title:  "[BOJ/백준] 28279. 덱 2"
categories: CodingTest
tag: [deque, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/28279>



  
  
# 과정

1. 명령을 실행할 덱(d)을 만들어준다.
2. a[0]이 1이라면 d의 앞쪽에 a[1]을 추가한다.
3. a[0]이 2라면 d이 뒤쪽에 a[1]을 추가해준다.
4. a[0]이 3라면 d가 비어있지 않으면 덱에 제일 앞에 있는 수를 출력하고 pop해준다.  
비어있으면 -1을 출력한다.
5. a[0]이 4라면 d가 비어있지 않으면 덱에 제일 뒤에 있는 수를 출력하고 pop해준다.  
비어있으면 -1을 출력한다.
6. a[0]이 5이라면 d의 길이를 출력해준다.
7. a[0]이 6라면 d가 비어있으면 1을 출력 그렇지 않으면 0을 출력해준다.
8. a[0]이 7라면 d에 수가 있으면 d에서 첫번째 수를 출력해준다.  
비어있으면 -1을 출력해준다.
9. a[0]이 9이라면 d에 수가 있으면 d에서 마지막 수를 출력해준다.  
비어있으면 -1을 출력해준다.

# 정답 코드

<script src="https://gist.github.com/kghees/cc5cbd1f70d382a468d79ebbb9bd8470.js"></script>
    




