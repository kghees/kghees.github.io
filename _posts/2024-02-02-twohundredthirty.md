---
layout: single
title:  "[SWEA] 2806. N-Queen"
categories: CodingTest
tag: [D3, c++]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AV7GKs06AU0DFAXB&categoryId=AV7GKs06AU0DFAXB&categoryType=CODE&problemTitle=n-&orderBy=FIRST_REG_DATETIME&selectCodeLang=ALL&select-1=&pageSize=10&pageIndex=1>


  
# 과정
1. queen을 놓을 수 있는 경우의 수를 세주기 위한 cnt를 만들어준다.
2. queen을 놓을 배열 d를 만들어준다.
3. t개 만큼 돌아야하므로 dfs하기전에 cnt = 0으로 초기화 시켜준다.
4. 0~n-1까지 돌려야하므로 0부터 dfs해준다.
5. n개 놔졌으면 퀸을 정상적으로 배치 했으므로 cnt++ 해주고 return해준다.
6. 그게 아닐경우 0~n까지 d[x]자리에 i를 배치하고 맞게 놓아졌는지 check(x)해주고   true이면 x+1로 넘어간다.
7. d[x] == d[i] 이면 같은 열 ,   
abs(d[x] - d[i]) == x - i 이면 대각선 상에   
있으므로 false를 return해주고 다 만족 했을 경우 true를 return해준다.
8. dfs가 끝나면 출력에 맞게 cnt를 출력해준다.
  



# 정답 코드
<script src="https://gist.github.com/kghees/bf28aee957446516cd0418904470c9aa.js"></script>
  




