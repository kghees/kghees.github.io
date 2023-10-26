---
layout: single
title:  "[SWEA] 14555. 공과 잡초"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AYGtoa3qARcDFARC&categoryId=AYGtoa3qARcDFARC&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=4>

  
  
# 과정
1. 공과 잡초를 구분하기 위한 stack과 공의 갯수를 넣어줄 cnt를 초기화한다.
2. 공의 시작이므로 (가 들어오면 stack에 넣어준다.
3. 잡초가 들어오면 그 전에 (가 있다면 공이 될 수도 있으므로  
stack에서 pop해주고 cnt에 1을 더해주고  
없을 경우 잡초를 stack에 추가해준다.
4. )가 들어오면 그 전에 잡초가 있다면 공이 될 수 있으므로   
stack에서 pop해주고 cnt에 1을 더해준다.
5. )가 들어왔을 때 그 전이 잡초가 아닌 여는 괄호 였다면 또 한  
공이 될 수 있으므로 stack에서 pop해주고 cnt에 1을 더해준다.
6. 테스트 케이스 번호와 cnt 값을 출력해준다.







# 정답 코드
<script src="https://gist.github.com/kghees/d882c46b258802461638343d8a8bb6f7.js"></script>