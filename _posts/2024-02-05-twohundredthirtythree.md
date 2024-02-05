---
layout: single
title:  "[백준] 15649. N 과 M(1)"
categories: CodingTest
tag: [Backtracking , c++]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/15649>



  
  
# 과정
1. arr은 수열을 저장할 배열을 check는 방문확인할 배열을 만들어준다.
2. dfs에서 길이가 m과 같아지면(수열의 길이가 m)  
m개 출력에 맞게 출력해주고 return 해준다.
3. 1부터 n까지의 자연수 범위 안에서 이미 골랐다면 넘어가고  
안골랐던 거면 arr배열에 추가해주고 check배열에 방문확인 해준다.  
그리고 다음 재귀로 넘어가고 넘어 갔다 오면 방문 해제 및 arr배열에서 초기화 해준다.



# 정답 코드
<script src="https://gist.github.com/kghees/a05c8950502588f1ec41e4fd3e4053e5.js"></script>
  




