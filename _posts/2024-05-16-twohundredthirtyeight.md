---
layout: single
title:  "[BOJ/백준] 14501. 퇴사"
categories: CodingTest
tag: [DP,브루트포스, c++]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/14501>



  
  
# 과정  
1. 각 날짜에 맞는 상담 기간 및 금액을 벡터에 넣기 위해 com이라는 구조체를 day(상담 일수), cost(상담 수익)으로 만들어준다.  

2. v에 각 상담 일수와 상담 수익을 받아준 후   
dfs(현재 지난 날짜, 현재 수익)으로 시작해 준다.  

3. 기저 조건으로 x(현재 지난 날짜)가 n일을 넘어가면 안되므로 넘어가면
return 해준다.  

4. 최대 수익 비교를 하기 위한 조건을 x(현재 지난 날짜)가 n일째 일 떄 최대 수익을 비교해주고 다른 경우를 비교하기 위해 return 해준다.  

5. dfs(x+1,cnt) : 현재 상담을 하지 않고 그냥 다음 날짜로 넘어가는 경우  
dfs(x+v[x].day, cnt + v[x].cost) : 현재 날짜에 상담을 하기 때문에  
x(현재 지난 날짜)에 x일에 해당하는 상담 일 수를 더해주고 cnt(현재 수익)에는 x일에 해당하는 수익을 더해준다.  
 
6. res(최종 최대 수익)을 출력해준다.




# 정답 코드
<script src="https://gist.github.com/kghees/83f08852cc66cb8766e1c8d5f1d248d2.js"></script>




