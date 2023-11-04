---
layout: single
title:  "[BOJ/백준] 2644. 촌수계산"
categories: CodingTest
tag: [dfs, bfs, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/2644>



  
  
# 과정
## 1. DFS
1. 방문했는지 확인할 check 리스트와 촌수를 구하기 위한 res 리스트를 만들어준다.
2. check에 x를 방문했다고 바꿔준다.(True)
2. a[x]에 있는 i를 방문하지 않았다면 res[i]에 res[x]값에 1을 더해준다.  
그리고 i에 대해 dfs()함수를 실행시켜준다.
3. res[y]값이 0이 아니라면 촌수가 있는 것이므로 res[y]값을 출력해준다.  
0이라면 관계가 없는 것이므로 -1을 출력해준다.
  

## 2. BFS
1. 방문했는지 확인할 check 리스트와 촌수를 구하기 위한 res 리스트를 만들어준다.
2. q를 만들고 q에 x를 추가해주고 check에 x 방문을 표시(True)한다.
3. a[x]에 있는 i를 방문하지 않았다면 check에 방문 표시(True)를 해주고 res[i]에 res[x]값에 1을 더해준다.  
그리고 i를 q에 추가해준다.
4. res[y]값이 0이 아니라면 촌수가 있는 것이므로 res[y]값을 출력해준다.  
0이라면 관계가 없는 것이므로 -1을 출력해준다. 




# 정답 코드
1. DFS
<script src="https://gist.github.com/kghees/6c349e337de4ffcb1fb6720fd678a345.js"></script>
  
    
2. BFS
<script src="https://gist.github.com/kghees/c06f87e6bf4f1fdb788ea1466b75170f.js"></script>
  
    




