---
layout: single
title:  "[BOJ/백준] 19942. 다이어트"
categories: CodingTest
tag: [브루트포스, backtracking,비트마스킹]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/19942>



  
  
# 과정  
1. 5개의 값을 받아야 하니 각각의 이름으로 구조체를 만들어 주었다.
2. 모든 조합을 짜야하므로 dfs 함수를 만들어 주었다.
3. idx가 모든 조합의 갯수(v.size)가 된다면 현재 조합의 단백질, 탄수화물, 지방, 비타민의 합을 구해준다.

4. 각각의 단백질, 탄수화물, 지방, 비타민의 합이 조건에 부합한다면  
현재 재료 조합의 가격을 구해주고 현재 조합을 벡터에 넣어준다.

5. 현재 재료의 조합의 가격이 res에 있는 값 보다 작거나  
현재 값과 같은데 사전 순으로 빠르다면 res값 과 조합 벡터 값을 갱신 해준다.  
(벡터크기 비교로 사전 순을 비교 해줄 수 있다.)

6. dat배열에 1을 넣고 dfs를 돌리고 0으로 만들어주고 dfs를 돌리면 모든 조합을 만들어줄 수 있다.

7. 결과 값으로 res값이 1e9 그대로 라면 -1을 출력해주고  
그게 아니라면 res값과 최소 조합의 경우를 출력해준다.
 





# 정답 코드1
<script src="https://gist.github.com/kghees/30f0f9ae58e9c7a1de5904224206eba3.js"></script>  

# 정답 코드2(비트마스킹)  
<script src="https://gist.github.com/kghees/3e0fac9f7ec100bf11f3629f618fa822.js"></script>



