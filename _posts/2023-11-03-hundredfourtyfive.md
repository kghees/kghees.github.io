---
layout: single
title:  "[BOJ/백준] 2667. 단지번호붙이기"
categories: CodingTest
tag: [bfs, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/2667>



  
  
# 과정
## 1. DFS
1. 몇개 단지가 있는지 셀 res와 단지안의 집의 수를 셀 cnt를 0으로 초기화 해준다.
2. a[i][j]가 1일때 dfs(i,j)가 True라면 단지가 하나 있는 것이므로 res에 1을 더해주고 arr에 집의 수를 추가해주고 cnt를 0으로 초기화해준다.
3. 단지를 셀 방향벡터 dx,dy를 만들어준다.
4. x,y가 n의 범위 안에 없다면 False를 return해주고  
a[x][y]가 1이라면 a[x][y]를 세었으니 0으로 해주고 cnt에 1을 더해준다.
5. 4가지 방향에 대해 dfs()함수를 실행시켜주고 조건을 모두 만족하면 True를 return해주고 아니라면 False를 return해준다.
6. res값을 출력해주고 단지 안의 집의 수를 내림차순 출력해준다.  
  

## 2. BFS
1. 단지의 수를 셀 res를 0으로 초기화 해준다.
2. a[i][j]가 1이라면 res에 1을 더해주고 bfs(i,j) 값을 arr에 추가해준다.
3. q를 만들고 x,y를 q에 추가해주고 a[x][y]를 0으로 바꿔준다.
4. 집의 수를 셀 cnt를 1로 초기화해준다.
5. 4가지 방향에 대해 nx,ny가 범위를 벗어나면 넘어가고  
a[nx][ny]가 1이라면 a[nx][ny]를 0으로 바꿔주고 cnt에 1을 더해주고 q에 nx,ny를 추가해준다.
6. res값을 출력해주고 단지 안의 집의 수를 내림차순 출력해준다.  




# 정답 코드
1. DFS
<script src="https://gist.github.com/kghees/27134b75c9e88f3c0965bdd8bf1db56f.js"></script>
  
    
2. BFS
<script src="https://gist.github.com/kghees/b6dc6a5e9d6698a24ccdfcaf76715a96.js"></script>
  
    




