---
layout: single
title:  "[백준] 2178. 미로 탐색"
categories: CodingTest
tag: [BFS , c++]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/2178>



  
  
# 과정
1. 4가지 방향에 대해서 dx,dy를 만들어준다.
2. miro는 미로를 저장할 배열, check는 방문했는지 확인할 배열을 만들어준다.
3. 공백이 없으므로 string형태로 입력 받아서 miro배열에 숫자 형태로 미로를 저장해준다.
4. x,y에 대해 방문확인 해주고 nx,ny가 범위에서 벗어나지 않고  
miro 배열에서 1일때와 아직 방문하지 않았다면 nx,ny에 대해 방문확인 해주고  
miro배열에서 그 전 간 횟수에 1을 더해서 저장해주고 q에 push해준다.
5. n-1,m-1번째 값이 미로를 간 최소 칸 수 이므로 출력해준다.



# 정답 코드
<script src="https://gist.github.com/kghees/d81cd1645d50377f4c90ad16c0d89fde.js"></script>
  




