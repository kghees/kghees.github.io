---
layout: single
title:  "[BOJ/백준] 14503. 로봇 청소기"
categories: CodingTest
tag: [구현, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/14503>



  
  
# 과정

1. 방문했는지 확인할 check 리스트를 만들어 주고 시작점을 바로 방문확인(True)해준다.
청소하는 칸의 개수를 셀 cnt를 정의해준다.
2. 아직 청소를 안했다는 의미로 ans를 0으로 정의해준다.
3. 4방향을 돌고 d를 왼쪽 방향으로 한칸 돌려준다.
4. nx,ny가 범위에 있고 방문하지 않았을 때 a[nx][ny]가 0이라면
방문 확인(True)해주고 cnt에 1을 더해주고 청소 했으니 ans = 1로 바꾸어준다.  
그리고 r과c의 위치를 업데이트 해주고 break해준다.
5. 만약 네방향 모두 청소를 할 수 없을 때(ans = 0)  
현재 방향에서 뒤쪽이 1이라면 더 이상 진행 할 수 없으니 cnt를 출력해주고 break 해준다.
6. 벽이 아니라면 한칸 후진할 수 있으니 r,c의 위치를 한칸 뒤로 업데이트 해준다.




# 정답 코드

<script src="https://gist.github.com/kghees/f9131ae4e57ebcfc996c1edeaa6c8eaa.js"></script>
  
    




