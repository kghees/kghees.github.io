---
layout: single
title:  "[SWEA] 3975. 승률 비교하기"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWIX_iFqjg4DFAVH&categoryId=AWIX_iFqjg4DFAVH&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=9>


  
  
# 과정
1. 한번에 결과를 출력하기 위한 res 리스트를 만들어준다.
2. x에는 앨리스의 승률 값을 y에는 밥의 승률 값을 넣어준다.
3. x,y가 같다면 승률이 같은 것이므로 res에 'DRAW'를 추가해준다.
4. x가 y보다 크다면 앨리스 승률이 더 높은 것이므로 res에 'ALICE'를 추가해준다.
5. 나머지 경우에는 밥의 승률이 더 높은 것이므로 res에
'BOB'을 추가해준다.
6. 테스트 케이스 번호와 res에 저장된 값을 순서대로 출력해준다.


  




# 정답 코드
<script src="https://gist.github.com/kghees/643218e7239007019a95a09a0b602e43.js"></script>
      