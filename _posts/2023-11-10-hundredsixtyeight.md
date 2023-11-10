---
layout: single
title:  "[BOJ/백준] 24480. 알고리즘 수업 - 깊이 우선 탐색2"
categories: CodingTest
tag: [dfs, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/24480>



  
  
# 과정

1. 정점과 간선에 맞게 a리스트에 u,v를 넣어준다.
2. 방문확인과 순서를 저장 하기 위한 check리스트를 만들어준다.
3. 방문순서를 저장할 cnt를 1로 정의해준다.
4. 내림차순 방문을 위해 정렬해준다.
5. r부터 dfs()함수를 실행시킨다.
6. check리스트에 x에 대해 방문순서를 저장한다.
7. a[x]안에 있는 i에 대해 방문하지 않았다면 cnt에 1을 더해주고 dfs(i)를 실행시켜준다.
8. 각 정점들의 방문순서를 출력한다.



# 정답 코드

<script src="https://gist.github.com/kghees/99fb496d6beae492752fb0117678fbdc.js"></script>
  
    




