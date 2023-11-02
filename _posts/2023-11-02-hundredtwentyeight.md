---
layout: single
title:  "[SWEA] 2814. 최장 경로"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AV7GOPPaAeMDFAXB&categoryId=AV7GOPPaAeMDFAXB&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=11&&&&&&&&&&>


  
  
# 과정
1. a리스트에 정점들을 넣어준다.
2. 정점의 개수는 최소 1개이므로 cnt를 1로 정의한다.
3. 1부터 n + 1까지를 반복문의 범위로 설정하며, check[i]를 방문처리(True) 해주고 dfs(i,1) 함수를 호출한다.  
(i부터 경로를 탐색, 정점의 개수는 1개)
4. dfs(x,k) 함수에서 cnt에 k 값과 cnt 값중 큰 값을 넣어준다.
5. 정점끼리 이어져 있어야 하므로 i가 a[x]안에 있을때를  반복문의 범위로 설정하며,   
만약 i가 방문처리 되어 있지않으면  i를 방문처리해주고 
dfs() 함수를 재귀 호출한 뒤 방문처리를 해제한다.
6. 테스트 케이스 번호와 cnt를 출력해준다.

 




# 정답 코드
<script src="https://gist.github.com/kghees/43b73f59911951640a7e72100d943d3f.js"></script>