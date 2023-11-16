---
layout: single
title:  "[SWEA] 1288. 새로운 불면증 치료법"
categories: SWEA
tag: [python, D2]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=2&contestProbId=AV18_yw6I9MCFAZN&categoryId=AV18_yw6I9MCFAZN&categoryType=CODE&problemTitle=&orderBy=RECOMMEND_COUNT&selectCodeLang=PYTHON&select-1=2&pageSize=10&pageIndex=3>




  
  
# 과정

1. 0~9까지 숫자를 봤는지 셀 num 리스트를 만들어준다.
2. 몇번째 까지 세었는지 확인할 cnt를 1로 해준다.
3. num리스트에 0이 없으면 끝난 것이므로 break해준다.
4. x에 n*cnt를 문자열화 한 걸 넣어서 x에 있는 숫자들을 num리스트에 1씩 더해주고 cnt에 1을 더해준다.
5. 테스트 케이스 번호와 x*n을 출력해준다.



# 정답 코드
<script src="https://gist.github.com/kghees/72888b2cd1ef74d87b17789db512d6c9.js"></script>


