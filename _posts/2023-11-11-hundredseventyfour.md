---
layout: single
title:  "[SWEA] 1223. [S/W 문제해결 기본] 6일차 - 계산기2"
categories: SWEA
tag: [python, D4]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=4&contestProbId=AV14nnAaAFACFAYD&categoryId=AV14nnAaAFACFAYD&categoryType=CODE&problemTitle=&orderBy=INQUERY_COUNT&selectCodeLang=PYTHON&select-1=4&pageSize=10&pageIndex=2>




  
  
# 과정
1. 연산 기호 이외의 숫자를 저장할 res와 연산 기호를 저장할 stack을 정의해준다.
2. '+'를 만나면 stack이 빌 때까지 res에 stack에 있는 것들을 pop해주고 i를 stack에 추가해준다.
3. '*'을 만나면 stack의 마지막이 '*'이 아닐때(연산자 우선순위를 생각해야하므로) 까지 res에 stack에 있는 것들을 pop해주고 i를 stack에 추가해준다.
4. 숫자를 만나면 res에 더해준다.
5. stack에 남아있는게 있으면 모두 res에 더해주고 stack을 초기화해준다.
6. res에서 '+'를 만나면 stack에 있는 숫자 두개를 더해서 다시 stack에 추가해준다.  
'*'를 만나면 stack에 있는 숫자 두개를 곱해서 다시 stack에 추가해준다.    
숫자를 만나면 stack에 정수화해 추가해준다.
7. 테스트케이스 번호와 stack에 있는 결과 값을 출력해준다.




# 정답 코드
<script src="https://gist.github.com/kghees/f6270338de3c26f86cf65242a2d5ebc5.js"></script>
    


