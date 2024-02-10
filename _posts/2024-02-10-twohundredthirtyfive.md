---
layout: single
title:  "[BOJ/백준] 2667. 단지번호붙이기"
categories: CodingTest
tag: [BFS, c++]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/2667>



  
  
# 과정
1. 단지번호배열을 저장할 number를 범위에 맞게 만들어주고 결과 값을 저장할 dat배열도 만들어준다.
2. 공백없이 입력이므로 string형으로 받아서 정수로 바꿔서 저장해준다.
3. number[i][j]가 1이라면 근처 단지내의 집의수를 세기위해서 bfs함수를 돌려주고 갔다오면 단지수가 1개있는 것이므로 res를 증가시켜준다.
4. bfs함수에서 4방향에 대해서 조건에 맞다면 cnt 1 증가시켜주고 최종 cnt값을 return해준다.
5. 단지수와 단지내 집의 수를 오름차순으로 정렬해 출력해준다.




# 정답 코드
<script src="https://gist.github.com/kghees/487ae311f0e574471ae9d7397810f9a2.js"></script>




