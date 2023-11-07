---
layout: single
title:  "[SWEA] 1227. [S/W 문제해결 기본] 7일차 - 미로2"
categories: SWEA
tag: [python, D4]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=4&contestProbId=AV14wL9KAGkCFAYD&categoryId=AV14wL9KAGkCFAYD&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=4&pageSize=10&pageIndex=1>




  
  
# 과정
## 1. DFS
1. a[i][j]가 2일때 dfs(i,j)를 실행시킨다.(가는 길이 있다면 한번만 실행시켜도 목적지까지 갈 것이다.)
2. 4가지 방향 벡터dx,dy를 만들어준다.
3. a[x][y]를 1로 만들어주고 4가지 방향에 대해서 반복문을 돌려준다,
4. nx,ny가 범위안에 있을 때 a[nx][ny]가 0이라면 dfs(nx,ny)를 실행 시켜주고   
a[nx][ny]가 3이라면 목적지이니 1로 바꿔주고 return해준다.
5. a[i][j]에 3이 존재하면 목적지에 갈 수 없으니 res에 0을 넣어준다.
6. 테스트 케이스 번호와 res 값을 출력해준다.

## 2. BFS
1. a[i][j]가 2일때 bfs(i,j)를 실행시킨다.(가는 길이 있다면 한번만 실행시켜도 목적지까지 갈 것이다.)
2. 4가지 방향 벡터dx,dy를 만들어준다.
3. q를 만들고 q에 x,y를 넣어준다. 그리고 a[x][y]를 1로 바꾸어준다.
4. 4가지 방향에 대해 nx,ny가 범위 안에 있을 때 a[nx][ny]가 0이라면 1로 바꾸어 주고 q에 nx,ny를 추가해준다.
5. a[nx][ny]가 3이라면 1로 바꾸어주고 목적지에 도달했으니 break해준다.
6. a[i][j]에 3이 존재하면 목적지에 갈 수 없으니 res에 0을 넣어준다.
7. 테스트 케이스 번호와 res 값을 출력해준다.




# 정답 코드
1. DFS
<script src="https://gist.github.com/kghees/809b7a62b0f21e611ca443489330157b.js"></script>
  
    
2. BFS
<script src="https://gist.github.com/kghees/9f707c80c356f09d88a426ef0c58619f.js"></script>
  
    




