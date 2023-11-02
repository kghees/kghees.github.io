---
layout: single
title:  "[SWEA] 4615. 재미있는 오셀로 게임"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWQmA4uK8ygDFAXj&categoryId=AWQmA4uK8ygDFAXj&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=10>


  
  
# 과정
1. 오셀로 게임판을 위한 a 리스트를 만들어서 처음 시작하는 배치에 흑돌과 백돌을 위치에 넣어준다.
2. 돌 색을 바꿔야하는 위치를 넣을 ans 리스트를 만들어준다.
3. 돌의 위치를 더해줄 dx,dy 위치 벡터를 만들어준다.
4. 현재 돌을 넣을 위치에서 8가지 방향의 위치를 따져주면서 돌의 색깔을 바꾸어준다.
5. 흑돌과 백돌의 수를 세어준다.
6. 테스트 케이스 번호와 흑돌의 수, 백돌의 수를 출력해준다.  

  



  



# 정답 코드
<script src="https://gist.github.com/kghees/4a90f0c2b0cacc710f5bfc22ab83edab.js"></script>
      