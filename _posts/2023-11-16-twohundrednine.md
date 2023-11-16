---
layout: single
title:  "[SWEA] 1974. 스도쿠 검증"
categories: SWEA
tag: [python, D2]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=2&contestProbId=AV5Psz16AYEDFAUq&categoryId=AV5Psz16AYEDFAUq&categoryType=CODE&problemTitle=&orderBy=RECOMMEND_COUNT&selectCodeLang=PYTHON&select-1=2&pageSize=10&pageIndex=1>




  
  
# 과정

1. 스도쿠를 검증할 res를 1로 정의해준다.
2. num은 가로 스도쿠를 검사, num1은 세로 스도쿠를 검사 하기 위해 만들어준다.
3. 스도쿠의 가로 수들을 num에 더해주고 세로 수들을 num1에 더해준다.
4.  만약 num과 num1에 1의 갯수가 9가 아니라면 잘못된 스도쿠 이므로 res를 0으로 바꾸어주고 break해준다.
5. 3x3 칸을 검사하기위해 num2를 만들어준다.
6. 3x3 칸의 수들을 num2에 더해주고 1의 갯수가 0가 아니라면 res에 0을 넣어주고 break해준다.
7. 테스트 케이스 번호와 res를 출력해준다.


# 정답 코드
<script src="https://gist.github.com/kghees/821362d3d9efcb66267f946fa3f70f61.js"></script>



