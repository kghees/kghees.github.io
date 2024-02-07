---
layout: single
title:  "[BOJ/백준] 1012. 유기농 배추"
categories: CodingTest
tag: [DFS, BFS, c++]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/1012>



  
  
# 과정
## 1
1. 배추를 저장할 배열 cabbage를 n,m의 범위에 맞게 만들어준다.
2. 테스트케이스마다 cabbage를 초기화할 init()함수를 만들어준다.
3. bfs()한번 돌고오면 한마리의 지렁이가 필요하므로 res++ 해준다.
4. x,y는 바로 먹은 걸로 처리하고 좌우상하에 대해 탐색해 아직 안먹었으면  
먹어주고 다음 방향 탐색 처리를 해준다.
5. res를 출력해준다. 
  
## 2
1. bfs푸는 방식과 똑같지만 재귀를 돌려준다는 점에서만 다르다.



# 정답 코드
## 1
<script src="https://gist.github.com/kghees/6b8c89c7aa1a831911300dbcbfd32ced.js"></script> 
  
## 2
<script src="https://gist.github.com/kghees/e6d6c8f251c6339139ffb09a4d02545a.js"></script>




