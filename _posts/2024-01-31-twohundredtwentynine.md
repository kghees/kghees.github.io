---
layout: single
title:  "[백준] 24479. 알고리즘 수업 - 깊이 우선 탐색 1"
categories: CodingTest
tag: [DFS, c++]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/24479>


  
# 과정
1. 배열을 저장하기 위한 a벡터와 방문 순서를 저장하기 위한 check벡터를 만들어준다.
2. 오름차순으로 방문해야하므로 정렬해주기
3. 방문 할 때 마다 방문 순서(cnt)를 넣어준다. 
4. 방문하지 않았다면 다음 방문 순서를 넣어주기 위해 cnt를 1증가시켜주고 방문 체크를 해준다.
5. check벡터에서 방문순서를 출력해준다.
  



# 정답 코드
<script src="https://gist.github.com/kghees/791301e46536bc0ce00ffadf2881055d.js"></script>
  




