---
layout: single
title:  "[SWEA] 1219. [S/W 문제해결 기본] 4일차 - 길찾기"
categories: SWEA
tag: [python, D4]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=4&contestProbId=AV14geLqABQCFAYD&categoryId=AV14geLqABQCFAYD&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=4&pageSize=10&pageIndex=1>




  
  
# 과정

1. a리스트 값을 d리스트에 길의 값들을 넣어준다.
2. 방문했는지 확인하기 위한 check리스트를 만들어준다.
3. dfs()에서 x값이 99이면 목적지에 도달한 것이므로 True를 return해준다.
4. d[x]안에 i값에 대해 방문하지 않았으면 방문확인(True) 해주고 dfs(i)에 대해 True값이 반환되면 True를 return 해준다.
5. dfs(0)이 True이면 목적지에 도달한 것이므로  
테스트 케이스 번호와 1을 출력해준다.
6. dfs(0)이 False이면 목적지에 도달하지 못한 것이므로  
테스트 케이스 번호와 0을 출력해준다.






# 정답 코드

<script src="https://gist.github.com/kghees/cdcb119c0b0c1cd1a56680a3b8dc6f35.js"></script>
  
    




