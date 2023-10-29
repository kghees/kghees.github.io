---
layout: single
title:  "[SWEA] 1493. 수의 새로운 연산"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AV2b-QGqADMBBASw&categoryId=AV2b-QGqADMBBASw&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=6>


  
  
# 과정
1. 그래프 값을 저장할 a리스트를 만들어 준다.
2. 규칙을 찾아 j가 1일때 a[i][j] = a[i-1][j] + i이고  
나머지 경우에는 a[i][j] = a[i][j-1] + x 한 후 x를 1증가시켜준다.
3. a리스트에서 p와 q의 i,j를 찾고 각각의 i값 j값을 더해준다.
4. 테스트 케이스 번호와 더한 i,j 값을 a리스트에서 출력해준다.





# 정답 코드
<script src="https://gist.github.com/kghees/9062cd777b0dfcd61089bde54b83b5e7.js"></script>