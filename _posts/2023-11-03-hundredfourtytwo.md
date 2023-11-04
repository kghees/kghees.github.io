---
layout: single
title:  "[BOJ/백준] 1260. DFS와 BFS"
categories: CodingTest
tag: [dfs, bfs, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/1260>



  
  
# 과정

1. 정점의 번호를 저장할 a리스트를 만들어준다.
2. 방문할 수 있는 정점이 여러개인 경우에는 작은 순서로 방문하라고 했으니 a를 내림차순 정렬해준다.
3. dfs 와 bfs에서 방문했는지 확인할 check1,check2를 만들어준다.
4. dfs()함수에서 x를 방문하면 바로 print해주고 a[x]안의 i에 대해서 방문했는지에 대해 check1하고 다시 dfs()함수를 실행시켜준다.
5. bfs()함수에서 x를 q에 넣고 꺼내고 바로 print해준다. a[x]안의 i에 대해서 방문했는지에 대해 check2하고 q에 i를 추가해준다.
6. dfs(start) 한줄 띄고 bfs(start)값을 출력해준다.  
  
# 정답 코드
<script src="https://gist.github.com/kghees/b8c8526c400b3f56c80931d6259416c4.js"></script>
  
    




