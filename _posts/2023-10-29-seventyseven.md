---
layout: single
title:  "[SWEA] 2806. N-Queen"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AV7GKs06AU0DFAXB&categoryId=AV7GKs06AU0DFAXB&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=6>

  
  
# 과정
1. 퀸을 저장할 d 리스트와 경우의 수를 저장할 cnt를 만들어준다.
2. 한줄씩 재귀할 dfs를 만들어준다.
3. x가 n과 같다면 모든행을 돌았다는 것이므로 cnt에 1을 더해준다.
4. 그게 아니라면 i 는 열번호 0부터 N 전까지 옮겨가면서 유망한곳 찾기이고 d[x]에 i 값을 저장한다.
5. 행,열,대각선 check함수가 true이면 백트래킹 안하고 계속 진행한다.
6. check함수에서 인덱스가 행 d[i] 값이 열이므로 열이 같거나 대각선이 같으면 False를 반환하고 무사히 다 통과하면 True를 반환한다. (대각선이 같은 경우는 행-행 = 열-열이 같으면 두개는 대각선상에 있는 것이다.)
7. 테스트 케이스 번호와 cnt를 출력해준다.





# 정답 코드
<script src="https://gist.github.com/kghees/53b1e841b4610e44dbda6b03a86bf8fd.js"></script>