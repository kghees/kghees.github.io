---
layout: single
title:  "[BOJ/백준] 1926. 그림"
categories: CodingTest
tag: [dfs, bfs, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/1926>



  
  
# 과정
## 1. DFS
1. 그림의 수를 저장할 res와 그림의 넓이를 저장할 cnt를 0으로 초기화 해주고 그림의 넓이들을 저장할 arr 리스트를 정의해준다.
2. a[i][j]가 1일때 dfs(i,j)도 True라면 그림이 하나 있는 것이므로 res에 1을 더해주고 arr에 그림의 넓이를 넣어준 뒤
cnt를 0으로 초기화해준다.
3. 4가지 방향 벡터dx,dy를 만들어준다.
4. x,y가 범위를 벗어나면 False를 return 해준다.
5. a[x][y]가 1일 때 a[x][y]를 0으로 바꿔주고 cnt에 1을 더해준다.
6. 4가지 방향에 대해 dfs()함수를 실행해준다.
7. arr에 값이 있다면 x에 arr중 가장 큰 값을 넣어주고  
값이 없다면 x에 0을 넣어준다.
8. res와 x를 출력해준다.
  

## 2. BFS
1. 그림의 수를 저장할 res를 0으로 초기화 해주고 그림의 넓이들을 저장할 arr 리스트를 정의해준다.
2. a[i][j]가 1일때 res에 1을 더해주고 bfs(i,j)값을 arr에 추가해준다.
3. 4가지 방향 벡터dx,dy를 만들어준다.
4. q를 만들어주고 q에 x,y를 추가시켜준다.  
cnt를 1로 초기화하고 a[x][y]를 0(cnt를 1로 초기화 했으니)으로 만들어준다.
5. 4가지 방향에 대해 nx,ny가 범위 안에 있고 a[nx][ny]도 1이라면 a[nx][ny]를 0로 바꾸고 cnt에 1을 더해준다.
그리고 q에 nx,ny를 추가해준다.
6. 한 영역의 넓이를 구한 cnt를 return해준다.
7. arr에 값이 있다면 x에 arr중 가장 큰 값을 넣어주고  
값이 없다면 x에 0을 넣어준다.
8. res와 x를 출력해준다.




# 정답 코드
1. DFS
<script src="https://gist.github.com/kghees/5fda456d865d59901c20e52f087e80bd.js"></script>
  
    
2. BFS
<script src="https://gist.github.com/kghees/eacccfd37a9e7d78ca8b165b6ab103fa.js"></script>
  
    




