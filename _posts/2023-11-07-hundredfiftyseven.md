---
layout: single
title:  "[SWEA] 1222. [S/W 문제해결 기본] 6일차 - 계산기1"
categories: SWEA
tag: [python, D4]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=4&contestProbId=AV14mbSaAEwCFAYD&categoryId=AV14mbSaAEwCFAYD&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=4&pageSize=10&pageIndex=1&&&&&&&&&&>




  
  
# 과정
1. 연산 기호 이외의 숫자를 저장할 res와 연산 기호를 저장할 stack을 정의해준다.
2. '+'를 만나면 stack이 빌 때까지 res에 stack에 있는 것들을 pop해주고 i를 stack에 추가해준다.
3. 숫자를 만나면 res에 더해준다.
4. stack에 남아있는게 있으면 모두 res에 더해주고 stack을 초기화해준다.
5. res에서 '+'를 만나면 stack에 있는 숫자 두개를 더해서 다시 stack에 추가해준다.
숫자를 만나면 stack에 정수화해 추가해준다.
6. 테스트케이스 번호와 stack에 있는 결과 값을 출력해준다.




# 정답 코드

<script src="https://gist.github.com/kghees/adda4aaaddfac6b55f6345f992f116e7.js"></script>
  
    

  
    




