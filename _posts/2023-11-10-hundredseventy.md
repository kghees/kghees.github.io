---
layout: single
title:  "[SWEA] 1861. 정사각형 방"
categories: SWEA
tag: [python, D4]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=4&contestProbId=AV5LtJYKDzsDFAXc&categoryId=AV5LtJYKDzsDFAXc&categoryType=CODE&problemTitle=&orderBy=INQUERY_COUNT&selectCodeLang=PYTHON&select-1=4&pageSize=10&pageIndex=1>




  
  
# 과정
1. 처음에 출발해야 하는 방 번호와 최대 몇 개의 방을 이동할 수 있는지를 저장할 ans 리스트를 만들어준다.
2. 이동한 방의 수를 세기 위해 cnt를 1로 정의해주고 x에 bfs(i,j)를 실행한 값을 넣어준다.
3. 4가지 방향벡터 dx,dy를 만들어준다.
4. 4가지 방향에 대해 nx,ny가 범위 안에 있고 현재 값에서 1을 더한게 이동할 값이라면 cnt에 1을 더해주고 q에 nx,ny를 넣어준다.  
실행이 끝나면 cnt값을 x에 return 해준다.
5. x(이동한 방의 수)가 ans[1]보다 크다면 ans[1]에 x값을 넣어주고 ans[0]에는 출발해야하는 방번호를 넣어준다.
6. x(이동한 방의 수)가 ans[1]와 같다면 ans[0]의 값이 a[i][j]보다 크다면 ans[0]에 a[i][j] 값으로 갱신해준다.(방의 개수가 최대인 방이 여럿이라면 그 중에서 적힌 수가 가장 작은 것을 출력)
7. 테스트 케이스 번호와 ans 리스트의 값을 차례로 출력한다.



# 정답 코드
<script src="https://gist.github.com/kghees/824a1a4fbd3d534689ce4fe67451fae0.js"></script>
    


