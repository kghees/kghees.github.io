---
layout: single
title:  "[BOJ/백준] 7576. 토마토"
categories: CodingTest
tag: [bfs, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/7576>



  
  
# 과정

1. q를 만들어주고 a[i][j]가 1일때의 i,j를 q에 저장해준다.
2. bfs()함수에서 nx,ny가 범위안(n,m)에 있고 a[nx][ny]가 0이라면 변할 수 있으므로 현재 값에 +1을 해 진행되는 일 수를 저장시켜준다.
3. res에 진행된 일 수를 저장한다.
4. 만약 a에 0이 존재하면 모두 변하지 못했으므로 res에 -1을 저장시켜준다.
5. res가 -1이라면 -1을 출력해주고 아니라면 걸린 일 수를 출력해준다.


# 정답 코드

<script src="https://gist.github.com/kghees/3c0bbbad40a23bb4010ba01b4b7ceaef.js"></script>
  
    




