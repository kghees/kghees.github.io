---
layout: single
title:  "[BOJ/백준] 2583. 영역 구하기"
categories: CodingTest
tag: [dfs, bfs, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/2583>



  
  
# 과정
## 1. DFS
1. 영역을 채울 ans리스트를 범위에 맞게 만들어준다.
2. a,b,c,d에 맞게 영역을 1로 채워준다.
3. 영역의 수를 저장할 res와 한 영역에 넓이를 셀 cnt와 
영역의 넓이를 저장할 arr을 각각 정의해준다.
4. ans[i][j]가 0일 때 dfs(i,j)도 True라면 영역이 있는 것이므로 res에 1을 더해주고 arr에 영역의 넓이(cnt)를 추가해주고 cnt를 0으로 초기화 해준다.
5. 4가지 뱡향 벡터 dx,dy를 만들어준다.
6. dfs함수에서 x,y가 범위를 벗어나면 바로 False를 return해준다.
7. ans[x][y]가 0이면 1로 바꾸어주고 cnt에 1을 더해준다.
8. 4가지 방향에 대해서 dfs()함수를 실행시켜준다.
9. res를 출력하고 arr에 있는 값들을 오름차순 출력해준다.
  

## 2. BFS
1. 영역을 채울 ans리스트를 범위에 맞게 만들어준다.
2. a,b,c,d에 맞게 영역을 1로 채워준다.
3. 영역의 수를 저장할 res와 
영역의 넓이를 저장할 arr을 각각 정의해준다.
4. ans[i][j]가 0일 때 bfs에서 return 받은 값을 arr에 추가해주고 res에 1을 더해준다.
5. 4가지 뱡향 벡터 dx,dy를 만들어준다.
6. bfs() 함수에서 q를 만들어주고 x,y를 q에 추가 해주고  
ans[x][y]를 1로 해주고 영역의 넓이를 셀 cnt도 1로 정의해준다.
7. 4가지 방향에 대해 nx,ny가 범위 안에 있고 ans[nx][ny]도 0이라면 ans[nx][ny]를 1로 바꾸고 cnt에 1을 더해준다.
그리고 q에 nx,ny를 추가해준다.
8. 한 영역의 넓이를 구한 cnt를 return해준다.
9. res를 출력하고 arr에 있는 값들을 오름차순 출력해준다.




# 정답 코드
1. DFS
<script src="https://gist.github.com/kghees/5fda456d865d59901c20e52f087e80bd.js"></script>
  
    
2. BFS
<script src="https://gist.github.com/kghees/eacccfd37a9e7d78ca8b165b6ab103fa.js"></script>
  
    




