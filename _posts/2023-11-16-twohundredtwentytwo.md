---
layout: single
title:  "[SWEA] 1940. 가랏! RC카!"
categories: SWEA
tag: [python, D2]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=2&contestProbId=AV5PjMgaALgDFAUq&categoryId=AV5PjMgaALgDFAUq&categoryType=CODE&problemTitle=&orderBy=RECOMMEND_COUNT&selectCodeLang=PYTHON&select-1=2&pageSize=10&pageIndex=3>




  
  
# 과정

1. 총 이동거리를 저장할 res와 속력을 저장할 x를 0으로 정의한다.
2. 만약 a[0]이 1이라면 가속이므로 x에 a[1]을 더해준다.
3. 만약 a[0]이 2일때 감속이므로 x-a[1]이 0보다 작으면 x는 0으로 해주고 0보단 크면 x에서 a[1]을 빼준다.
4. res에 x를 더해준다.
5. 테스트 케이스 번호와 res를 출력해준다.



# 정답 코드
<script src="https://gist.github.com/kghees/4179c836905f1cf96ee5cc09ca6564c0.js"></script>


