---
layout: single
title:  "[SWEA] 2005. 파스칼의 삼각형"
categories: SWEA
tag: [python, D2]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=2&contestProbId=AV5P0-h6Ak4DFAUq&categoryId=AV5P0-h6Ak4DFAUq&categoryType=CODE&problemTitle=&orderBy=RECOMMEND_COUNT&selectCodeLang=PYTHON&select-1=2&pageSize=10&pageIndex=1&&&&&&&&&&>




  
  
# 과정

1. 파스칼의 삼각형의 규칙에 맞게 a리스트를 만들고 a[0][0]에 1을 넣어준다.
2. j가 0이라면 바로 위의 수를 그대로 받기 때문에  
a[i][j] = a[i-1][j]가 된다.
3. i와 j가 같으면 바로 위의 수를 그대로 받기 때문에  
a[i][j] = a[i-1][j-1]가 된다.
4.  그외의 경우에는 대각선 왼쪽 위 와 오른쪽 위의 값을 더해서 넣어준다.
5. 테스트 케이스 번호를 출력해준다.
6. a리스트 값을 출력해준다.


# 정답 코드
<script src="https://gist.github.com/kghees/ed4f71ab1aa3d35a764804e313dafa66.js"></script>


