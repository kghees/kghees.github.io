---
layout: single
title:  "[BOJ/백준] 1697. 숨바꼭질"
categories: CodingTest
tag: [bfs, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/1697>



  
  
# 과정

1. 방문확인 할 check 리스트와 시간을 저장할 time리스트를 만들어준다.
2. bfs()함수에서 x를 q에 넣어주고 time[x] 가 출발지점이니 0을 넣어준다.
3. nx가 이동할 수 있는 x-1,x+1,x*2 라는 노드가 3개 생기는데  
이 3개의 노드가 최소,최대 값이 넘어가지 않고 방문하지 않았으면
방문 확인(True)해주고 3가지 노드중 하나로 움직였으니 그 전 값에서 1을 더해서 저장해준다.  
q에 nx를 넣고 계속 진행시켜준다.
4. time[k](동생 위치 까지 걸린 시간)을 출력해준다.




# 정답 코드

<script src="https://gist.github.com/kghees/73f091313b1ea7f3541753105dc385af.js"></script>
  
    




