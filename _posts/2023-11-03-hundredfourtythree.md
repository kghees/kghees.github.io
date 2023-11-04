---
layout: single
title:  "[BOJ/백준] 2178. 미로탐색"
categories: CodingTest
tag: [bfs, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/2178>



  
  
# 과정

1. 미로를 탐색하기 위한 방향벡터 dx,dy(위,아래,왼쪽,오른쪽)를 만들어준다.
2. bfs()함수에서 q를 만들고 x,y를 q에 넣어준다.
3. 4가지 방향에 대해서 n과m의 범위를 넘어가면 다음 방향으로  
또한 a[nx][ny]가 0이어도 다음 방향으로 넘어가준다.
4. 만약 a[nx][ny]가 1이라면 현재 미로좌표위치 값에서 1을 더해주면 지금까지 온 미로의 길이이다.
5. n,m의 위치에 값이 곧 지나야하는 칸의 길이 이므로 출력해준다.
  
# 정답 코드
<script src="https://gist.github.com/kghees/9f971cca1e5a6688ee28c35613899177.js"></script>
  
    




