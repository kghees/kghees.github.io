---
layout: single
title:  "[BOJ/백준] 15649. N과 M(2)"
categories: CodingTest
tag: [backtracking, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/15650>



  
  
# 과정

1. 중복확인을 할 check 리스트를 만들어준다.
2. 수열을 저장할 a 리스트를 만들어준다.
3. dfs()함수에서 m 길이의 수열을 만들어야 하므로 x와 m이 같으면 a리스트에 있는 수열을 print해주고 return해준다.
4. start~n 사이의 i에서 방문하지 않았다면 방문확인(True)해주고  
a에 i를 추가해주고 dfs(x+1,i+1)(길이 추가,오름차순)해준다.  
return했으면 다른 수열도 확인해야하니 check[i]에 대해 방문을 취소해주고(False) a리스트에서도 pop해준다. 
5. dfs(0,1)(길이0부터, 1부터 오름차순) 실행시켜준다.

# 정답 코드

<script src="https://gist.github.com/kghees/e73d6af1a07e8639cfb0888fda2c93a9.js"></script>
    




