---
layout: single
title:  "[SWEA] 1491. 원재의 벽 꾸미기"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AV2b9AkKACkBBASw&categoryId=AV2b9AkKACkBBASw&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=9>


  
  
# 과정
1. 최소 값을 넣을 res를 -1로 만들어준다.
2. 최소 값이 되는 r과c를 찾아야하기 때문에 r 값 고정해두고 c값을 늘려가는 방식으로 완전탐색을 해준다.
3. r x c가 n보다 크면 while문을 멈추고 그 안에서 c값을 늘려가면서 최소가 되는 r과c값을 찾아 최소값을 res에 넣어준다.
4. 테스트 케이스 번호와 res를 출력해준다.


  




# 정답 코드
<script src="https://gist.github.com/kghees/b2e40b22e9bb72b6e65157b9fe569db5.js"></script>
      