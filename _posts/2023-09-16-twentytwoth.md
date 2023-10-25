---
layout: single
title:  "[BOJ/백준] 실버1 1149번 RGB 거리"
categories: CodingTest
tag: [Algorithm, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/1149>


# 문제
RGB거리에는 집이 N개 있다. 거리는 선분으로 나타낼 수 있고, 1번 집부터 N번 집이 순서대로 있다.

집은 빨강, 초록, 파랑 중 하나의 색으로 칠해야 한다. 각각의 집을 빨강, 초록, 파랑으로 칠하는 비용이 주어졌을 때,   
아래 규칙을 만족하면서 모든 집을 칠하는 비용의 최솟값을 구해보자.

- 1번 집의 색은 2번 집의 색과 같지 않아야 한다.
- N번 집의 색은 N-1번 집의 색과 같지 않아야 한다.
- i(2 ≤ i ≤ N-1)번 집의 색은 i-1번, i+1번 집의 색과 같지 않아야 한다.


## 입력
첫째 줄에 집의 수 N(2 ≤ N ≤ 1,000)이 주어진다.   
둘째 줄부터 N개의 줄에는 각 집을 빨강, 초록, 파랑으로 칠하는 비용이 1번 집부터 한 줄에 하나씩 주어진다.   
집을 칠하는 비용은 1,000보다 작거나 같은 자연수이다.


## 출력
첫째 줄에 모든 집을 칠하는 비용의 최솟값을 출력한다.
  
  
# 과정
점화식을 먼저 세워보았는데
D[i][j] = i번 집을 색깔 j로 칠 했을 때   
나머지 집을 칠하는 비용의 최소값 으로 세웠다!  
j = 0 일때 빨강이면 i-1번째 집은 초록 아니면 파랑  
j = 1 일때 초록이면 i-1번째 집은 빨강 아니면 파랑
j = 2 일때 파랑이면 i-1번째 집은 빨강 아니면 초록
# 정답 코드
<script src="https://gist.github.com/kghees/bae8301bfd99b7fb05a9c2c5ae3e2a6b.js"></script>
  
    

# 시행 착오
색을 어떻게 분배해야할까에서 조금 시간이 걸렸던 거 같다. 하지만
집 색을 고정시켜두고 생각하니 금방 해결되었다!!

# 후기
조건을 보고 여러가지 선택지가 있으면
하나의 값을 고정 시켜두고 생각해보자!