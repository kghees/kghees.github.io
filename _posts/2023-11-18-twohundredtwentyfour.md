---
layout: single
title:  "[BOJ/백준] 15721. 번데기"
categories: CodingTest
tag: [브루트포스, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/15721>



  
  
# 과정

1. 몇번째 뻔, 몇번째 데기 인지 저장할 res 리스트와  
뻔을 세어줄 b 데기를 세어줄 d 회차를 세어줄 n을 각각 정의해준다.
2. 이전 회차의 뻔을 m에 넣어주고 n(회차)에 1을 더해준다.
3. 처음에 뻔-데기-뻔-데기 이므로 2회 반복해서 b,d를 res에 추가해주고 1씩 더해준다
4. 회차에 맞게 뻔,데기를 res에 추가하고 1씩 더해준다.
5. 구하려던 번째가 이전 뻔과 현재 뻔사이에 있다면 t값의 인덱스를 찾아서 사람수로 나머지 계산 해주고 출력 후 break해준다. 


# 정답 코드

<script src="https://gist.github.com/kghees/76e1de0b498b9c1cb679813a6b10ebd2.js"></script>




