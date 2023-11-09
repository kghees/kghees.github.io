---
layout: single
title:  "[SWEA] 1238. [S/W 문제해결 기본] 10일차 - Contact"
categories: SWEA
tag: [python, D4]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=4&contestProbId=AV15B1cKAKwCFAYD&categoryId=AV15B1cKAKwCFAYD&categoryType=CODE&problemTitle=&orderBy=INQUERY_COUNT&selectCodeLang=PYTHON&select-1=4&pageSize=10&pageIndex=1>




  
  
# 과정
1. a리스트의 값들을 연락망에 맞게 d리스트에 넣어준다.
2. 방문확인을 할 check리스트를 만들어준다.
3. 몇번째 순서에 들어갔는지 저장할 num리스트를 만들어준다.
4. bfs(start)를 실행시켜준다.
5. bfs()함수에서 q를 만들고 x를 q에 넣고 x에 대해 방문확인(True)해준다.
6. d[x]안에 있는 i를  방문하지 않았을 때 i에 대해 방문확인(True)해주고 num[i]에 전에(x)에 순서보다 1을더해서 저장해준다.
7. 결과 값을 저장할 res와 가장 큰 값을 찾기위한 k를 0으로 정의해준다.
8. res에 가장 마지막에 연결된 값을 저장한다.
9. 테스트 케이스 번호와 res 값을 출력한다.



# 정답 코드
<script src="https://gist.github.com/kghees/24dedfa79f6a17aa0a5b658b1b103ba5.js"></script>
    


