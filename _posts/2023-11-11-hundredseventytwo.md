---
layout: single
title:  "[BOJ/백준] 24445. 알고리즘 수업 - 너비 우선 탐색2"
categories: CodingTest
tag: [dfs, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/24445>



  
  
# 과정

1. 정점과 간선에 맞게 a리스트에 u,v를 넣어준다.
2. 방문확인과 순서를 저장 하기 위한 check리스트를 만들어준다.
3. 방문순서를 저장할 cnt를 1로 정의해준다.
4. r부터 bfs()함수를 실행시킨다.
5. check리스트에 x에 대해 방문순서를 저장한다.
6. 내림차순 방문을 위해 정렬해준다.
7. a[x]에 있는 i에 대해 방문하지 않았으면 cnt에 1을 더해주고  
chekc[i]에 방문순서를 넣어주고 i를 q에 추가해준다.
8. 각 정점들의 방문순서를 출력한다.



# 정답 코드

<script src="https://gist.github.com/kghees/58e8afe8acbe3c9b8fdd2c8c50099497.js"></script>
  
    




