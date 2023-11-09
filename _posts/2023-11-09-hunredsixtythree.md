---
layout: single
title:  "[SWEA] 1249. [S/W 문제해결 응용] 4일차 - 보급로"
categories: SWEA
tag: [python, D4]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=4&contestProbId=AV15QRX6APsCFAYD&categoryId=AV15QRX6APsCFAYD&categoryType=CODE&problemTitle=&orderBy=INQUERY_COUNT&selectCodeLang=PYTHON&select-1=4&pageSize=10&pageIndex=1>




  
  
# 과정

1. 가장 작은 복구 경로 시간을 저장할 ans리스트에 1e9를 넣고 만들어준다.
2. ans 리스트의 처음 값에 a 리스트 처음 값을 넣어준다.
3. bfs(0,0) (시작점이 (0,0)이므로) 실행시켜준다.
4. 4가지 방향에 대한 방향 벡터 dx,dy를 만들어준다.
5. 4가지 방향에 대해 nx,ny가 범위 안에 있을 때  
가려는 경로에 최소 값을 비교해서 저장시켜주고 q에 nx,ny를 추가해준다.
6. 테스트 케이스 번호와 도착 지점에서의 가장 작은 복구 경로 시간을 출력해준다.






# 정답 코드

<script src="https://gist.github.com/kghees/244e2c9af6039a080cf4e83cdf7be8df.js"></script>
  
    




