---
layout: single
title:  "[BOJ/백준] 5014. 스타트링크"
categories: CodingTest
tag: [bfs, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/5014>



  
  
# 과정

1. 방문 확인을 할 check리스트와 버튼의 수 저장을 위한 button리스트를 만들어준다.
2. bfs()함수에서 nx가 x+u(u만큼위),x-d(d만큼아래)의 두가지 노드중 범위를 벗어나지 않고 방문하지 않았다면  
방문 체크(True)해주고 button[nx]에 현재 버튼 수에 1을 더해서 저장해주고 q에 nx를 추가해준다.
3. 만약 button[g](g에서의 버튼 수)가 -1이라면 엘레베이터로 이동할 수 없으니 'use the stairs'를 출력해주고  
이동 가능 하면 button[g]를 출력해준다.



# 정답 코드

<script src="https://gist.github.com/kghees/fb3b0bb152c1732d495592db6f8244d2.js"></script>
  
    




