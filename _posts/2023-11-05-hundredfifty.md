---
layout: single
title:  "[BOJ/백준] 2468. 안전 영역"
categories: CodingTest
tag: [dfs, bfs, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/2468>



  
  
# 과정
## 1. DFS
1. 비의 양의 범위를 구하기 위해 m에 a리스트의 최대값을 넣어준다.
2. 안전 영역의 갯수를 저장할 res를 정의한다.
3. m의 범위에서 i에 해당하는 비의 양에서의 안전 영역을 세기 위해 cnt를 0으로 초기화 해주고 영역을 세었는지 확인하기 위해 check리스트를 만들어준다.
4. a리스트에서 i보다 크고 방문하지 않았다면 cnt에 1을 더하고 check리스트에 방문확인(True)를 한후 dfs함수를 실행시켜준다.
5. 위,아래,왼쪽,오른쪽을 확인할 dx,dy 방향벡터를 만들어준다.
6. dfs()에서 4가지방향에 대해 nx,ny가 n의 범위 안에 있고 아직 방문 하지 않았을 때 a[nx][ny]가 t보다 크다면 방문 확인(True)해주고 nx,ny에 대해서 dfs()함수를 실행시켜준다.
7. 각 i마다 res에 최대 값을 갱신시켜준다.
8. res를 출력해준다.
  

## 2. BFS
1. 비의 양의 범위를 구하기 위해 m에 a리스트의 최대값을 넣어준다.
2. 안전 영역의 갯수를 저장할 res를 정의한다.
3. m의 범위에서 i에 해당하는 비의 양에서의 안전 영역을 세기 위해 cnt를 0으로 초기화 해주고 영역을 세었는지 확인하기 위해 check리스트를 만들어준다.
4. a리스트에서 i보다 크고 방문하지 않았다면 bfs함수를 실행시키고 cnt에 1을 더해준다. 
5. 위,아래,왼쪽,오른쪽을 확인할 dx,dy 방향벡터를 만들어준다.
6. bfs()함수에서 q를 만들어주고 x,y를 q에 넣어주고 x,y에 대해 방문확인(True)을 해준다.
7. 4가지 방향에 대해 nx,ny가 범위 안에 있고 아직 방문 하지 않았을 때 a[nx][ny]가 t보다 크다면 방문확인(True)해주고
q에 nx,ny를 넣어준다.
8. 각 i마다 res에 최대 값을 갱신시켜준다.
9. res를 출력해준다.




# 정답 코드
1. DFS
<script src="https://gist.github.com/kghees/e8b08f9011d7ef3495a54c6a8ca6ca6b.js"></script>
  
    
2. BFS
<script src="https://gist.github.com/kghees/5d85830aa6373c85e3423454d3f132a1.js"></script>
  
    




