---
layout: single
title:  "[SWEA] 14413. 격자판 칠하기"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AYEXgKnKKg0DFARx&categoryId=AYEXgKnKKg0DFARx&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=11>


  
  
# 과정
1. 격자판을 판단할 check를 True로 정의해준다.
2. a리스트에 대해서 paint함수가 True이면 계속 확인하고
False이면 check 를 False로 바꾸고 break해준다.
3. dx,dy 방향벡터를 만들어준다.
4. 4가지 방향에 대해 a[nx][ny]가 '?'일 때 a[x][y] 값에 따라 문자를 넣어주고 a[nx][ny]와 a[x][y]가 같다면 틀린 격자판이므로 바로 False를 return해준다. 모두 검사 했을 때 이상이 없다면 True를 return해준다.
5. check가 True라면 테스트 케이스 번호와 possible을 출력해준다. 
False라면 테스트 케이스 번호와 impossible을 출력해준다.

 

  



  



# 정답 코드
<script src="https://gist.github.com/kghees/8c4c02f29c3e54866be3f61f07b35a9e.js"></script>
      