---
layout: single
title:  "[BOJ/백준] 2606. 바이러스"
categories: CodingTest
tag: [bfs, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/2606>



  
  
# 과정
## 1. DFS
1. 방문했는지 확인할 check 리스트를 만들어주고  
바이러스에 감염된 수를 저장할 cnt를 0 으로 초기화해준다.
2. dfs()함수를 만들어준다.
3. dfs에서 x를 방문했으니 True로 해주고 a[x]에 i에 대해 방문하지 않았다면 방문True를 해주고 cnt에 1을 더한후 dfs(i)에 대해서 실행시켜준다.
4. cnt값을 출력해준다.  
  

## 2. BFS
1. 방문했는지 확인할 check 리스트를 만들어주고  
바이러스에 감염된 수를 저장할 cnt를 0 으로 초기화해준다.
2. bfs()함수를 만들어준다.
3. q를 만들어주고 x를 q에 추가해주고 check[x]에 대해 True해준다.
4. a[x]에 i에 대해 방문하지 않았다면 방문True를 해주고 cnt에 1을 더하고 q에 i를 추가해준다.
5. cnt 값을 출력해준다.




# 정답 코드
1. DFS
<script src="https://gist.github.com/kghees/b6234004c89fa01e3c9c3a95eff28d5a.js"></script>  
  
    
2. BFS
<script src="https://gist.github.com/kghees/9866034920abd32dc2ed16993e3c3031.js"></script>
  
    




