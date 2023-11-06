---
layout: single
title:  "[BOJ/백준] 10451. 순열 사이클"
categories: CodingTest
tag: [dfs, bfs, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/10451>



  
  
# 과정
## 1. DFS
1. a리스트의 값을 순열의 배열에 맞게 정리하기 위해 d리스트를 만들고 d리스트에 순열의 배열에 맞게 값 들을 추가해준다.
2. 사이클을 확인할때 방문확인을 할 check리스트를 만들어주고  
사이클 수를 셀 cnt를 0으로 초기화해준다.
3. i순열을 방문하지 않았다면 방문확인(True)해주고 i에 대해 
dfs(i)를 실행시켜주고 cnt에 1을 더해준다.
4. d[x]에 들어있는 i에서 i를 방문하지 않았다면 방문확인(True)해주고 i에 대해 dfs(i)를 실행시켜준다.
5. cnt값을 출력해준다.
  

## 2. BFS
1. a리스트의 값을 순열의 배열에 맞게 정리하기 위해 d리스트를 만들고 d리스트에 순열의 배열에 맞게 값 들을 추가해준다.
2. 사이클을 확인할때 방문확인을 할 check리스트를 만들어주고  
사이클 수를 셀 cnt를 0으로 초기화해준다.
3. i순열을 방문하지 않았다면 i에 대해 bfs(i)를 실행시켜주고 cnt에 1을 더해준다.
4. bfs() 함수에서 q를 만들고 q에 x를 넣고 x에 대해 방문확인(True)해준다.
5. d[x]에 들어있는 i에서 i를 방문하지 않았다면 방문확인(True)해주고 i에 대해 i를 q에 추가해준다.
6. cnt값을 출력해준다.




# 정답 코드
1. DFS
<script src="https://gist.github.com/kghees/608e9918e765582e735116988b8c7a7d.js"></script>
  
    
2. BFS
<script src="https://gist.github.com/kghees/b11847b86d750d653bc4e72f4a44ce0d.js"></script>
  
    




